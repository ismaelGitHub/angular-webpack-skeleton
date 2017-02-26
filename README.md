# Angular-webpack2-skeleton
A simple skeleton project to use Angular4 (or 2.x.x, if you want to downgrade it), Webpack2, Boostrap 4 alpha and bootstrap-loader 2 beta together

I created this project as an example for this issue: https://github.com/shakacode/bootstrap-loader/issues/191#issuecomment-256352654
After that, I decided to update it based on https://github.com/Ks89/My-MEAN-website-client
And I created some branches for this issue: https://github.com/ampedandwired/html-webpack-plugin/issues/481

This project is a personal skeleton. If you want to use it feel free to fork it.
I share this with you as it is.

I'll update this project in the future and I'll change the name to another one when Angular4 will be released.


## News
- *02/26/2017* - Alpha 12 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *02/26/2017* - Alpha 11 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *02/26/2017* - Alpha 10 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *01/30/2017* - Alpha 9 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *01/28/2017* - Alpha 8 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *01/22/2017* - Alpha 7 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *01/21/2017* - Alpha 6 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)
- *01/15/2017* - Alpha 5 - Check [HERE](https://github.com/Ks89/Angular2-webpack2-skeleton/releases)


## Changelog

#### Alpha 12
- Fix for AppVeyor and Windows
- Bootstrap 4 customizations thanks to bootstrap-loader. In fact, I'm overriding bootstrap colors with different hash codes. The same technique is valid for all variables into [_variables.scss](https://github.com/twbs/bootstrap/blob/v4-dev/scss/_variables.scss)

#### Alpha 11
- MIT license :)

#### Alpha 10
- typescript 2.2
- big refactoring
- some fixes related to both css and scss webpack's loaders
- fix for e2e tests (issue #12)

#### Alpha 9
- typescript 2.1
- awesome-typescript-loader 3.0.0 beta

#### Alpha 8
- improve npm scripts names #15
- remove ./node_modules/.bin from npm scripts #13

#### Alpha 7
- AOT + Lazy Loading together (thanks to `ng-router-loader`)

#### Alpha 6
- AOT #9

#### Alpha 5
- HMR
- Lazy Loading
- Tree Shaking (with webpack2 and not with rollup)
- Third party services as codeclimate, appveyor, travis ci and coveralls
- Massive refactoring


## Install global dependencies
I created some scripts inside 'setup' folder to initialize the environment.
If you are already ready, you can execute this (`sudo` if you are using macOS):

- `npm install -g lite-server`

## Install local dependencies
- `npm install`

## Run with webpack-dev-server (developing mode)
- `npm start`

## Build the application in 'dist' folder (debug mode)
- `npm run build:dev`
- `cd dist`
- `lite-server`

## Build the application in 'dist' folder (production mode)
- `npm run build:prod`
- `cd dist`
- `lite-server`

## Build the application in 'dist' folder (production + AOT mode)
- `npm run build:prod:aot`
- `cd dist`
- `lite-server`

## Test (check coverage/html/index.html with the results)
- `npm test`

## Test e2e with protractor
- `npm run webdriver:update` (if you have problems, try again removing `./node_modules` and executing `npm install`)
- `npm run e2e`


## License

**MIT License**

Copyright (c) 2017 **Stefano Cappa**

**This license is valid to all my files in this repo**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<br/>
**Created by Stefano Cappa**
