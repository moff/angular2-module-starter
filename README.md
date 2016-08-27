# Angular 2 module to NPM package

[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](http://opensource.org/licenses/MIT)

Easy to use module starter for Angular 2.

Quick and easy installation - no setup hassle - just focus on your code.

There is a test Angular 2 app and a separate folder for your module. Module is imported into that app to test it, while developing.

## Requirements
- [NPM](https://npmjs.org/) - Node package manager


## Installation

- clone this repository
- run following commands: 
    - `typings install`
    - `npm install`


## Module development

Module files are in `module` folder. There is a module example in it.

Run `npm start` to compile and watch TypeScript files.

There is a `/module/module.ts` file where you set up your module class name - by default it's a `YourAwesomeModule`. Change it as you need and edit `/app/app.module.ts` where it should be imported into test app which you can see in a browser when you run `npm start`.

When your module is ready you can publish it - files from `module` folder will be used for a package.


## Publishing package

- describe your module well in README.md
- run `npm publish`

Notice! Make sure you have stored your user credentials as described here

## License

The repository code is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
