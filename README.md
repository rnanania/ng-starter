# Angular, NgRx, Angular Material, Flexbox layout Starter with Wijmo
by [@rnanania](https://github.com/rnanania/)


## Table of Content

  * [Live Demo](Demo Link)
  * [Getting Started](#getting-started)
  * [Useful Commands](#useful-commands)
  * [Make It Your Own](#make-it-your-own)
  * [Features](#features)
  * [Stack](#stack)
  * [Changelog](https://github.com/rnanania/ng-starter/blob/master/CHANGELOG.md)


## Getting started
```bash
git clone https://github.com/rnanania/ng-starter.git my-app
cd my-app
npm install
npm start
```


## Useful Commands
  * `npm start` - starts a dev server and opens browser with running app
  * `npm run test` - runs lint and tests
  * `npm run watch` - runs tests in watch mode
  * `npm run prod` - runs full prod build and serves prod bundle
  * `npm run prettier` - runs prettier to format whole code base (`.ts` and `.scss`) 
  * `npm run analyze` - runs full prod build and `webpack-bundle-analyzer` to visualize how much code is shipped (dependencies & application) 


## Make It Your Own
When using this starter project to build your own app you might consider some of the following steps:
  
  * use `search and replace` functionality of your favourite IDE to replace `nr` with `<your-app-prefix>`
  * rename project in `package.json` `name` property and set appropriate version (eg `0.0.0` or `1.0.0`)
  * rename app in `src/environments/` files (will be shown in browser tab)
  * delete pre-existing `CHANGELOG.md` (you will generate your own with future releases of your features)
  * remove or adjust links in the [footer](https://github.com/rnanania/ng-starter/blob/master/src/app/app.component.html#L79)
  * replace logo in `src/assets` folder ( currently 128 x 128 pixel `png` file )
  * adjust colors in `src/themes/default-theme.scss`
  * create a pull request in the [original repository](https://github.com/rnanania/ng-starter) to update `BUILT_WITH.md` [file](https://github.com/rnanania/ng-starter/blob/master/BUILT_WITH.md) with a link and short description of your project

 
## Features

* custom themes support (3 themes included)
* lazy-loading of feature modules
* lazy reducers
* localStorage ui state persistence
* `@ngrx/effects` for API requests
* fully responsive design
* angular-material and custom components in `SharedModule`

 
## Stack

* Angular
* ngrx
* Angular Material
* Bootstrap 4 (only reset, utils and grids)


## Troubleshooting

* **Blocking at emitting LicenseWebpackPlugin when npm start** - try using [cnpm](https://github.com/cnpm/cnpm) instead of npm


### Acknowledgements

Built with and uses [Angular CLI](https://github.com/angular/angular-cli)
Angular Starter project from tomastrajan [angular-starter](https://github.com/tomastrajan/angular-starter)

