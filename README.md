# typescript-boilerplate

Minimalistic boilerplate to jump-start a [Node.js][nodejs] project in [TypeScript][typescript] [2.9][typescript-29].

Provides a basic template, "batteries included":

+ [TypeScript][typescript] [2.9][typescript-29] to ES6 transpilation,
+ [TSLint][tslint] 5.x with [Microsoft recommended rules][tslint-microsoft-contrib],
+ [Jest][jest] unit testing and code coverage,
+ Type definitions for Node.js v8 and Jest,
+ [NPM scripts for common operations](#available-scripts),
+ a simple example of TypeScript code and unit test,
+ .editorconfig for consistent file format.

## Quick start

This project is intended to be used with v8 (LTS Carbon) release of [Node.js][nodejs] or newer and [NPM][npm]. Make sure you have those installed. Then just type following commands:

```sh
git clone https://github.com/jsynowiec/node-typescript-boilerplate
cd node-typescript-boilerplate
npm install
```

or just download and unzip current `master` branch:

```sh
wget https://github.com/jsynowiec/node-typescript-boilerplate/archive/master.zip -O node-typescript-boilerplate
unzip node-typescript-boilerplate.zip && rm node-typescript-boilerplate.zip
```

Now start adding your code in the `src` and unit tests in the `__tests__` directories. Have fun and build amazing things 🚀

### Unit tests in JavaScript

Writing unit tests in TypeScript can sometimes be troublesome and confusing. Especially when mocking dependencies and using spies.

This is **optional**, but if you want to learn how to write JavaScript tests for TypeScript modules, read the [corresponding wiki page][wiki-js-tests].

## Available scripts

+ `clean` - remove coverage data, Jest cache and transpiled files,
+ `build` - transpile TypeScript to ES6,
+ `watch` - interactive watch mode to automatically transpile source files, 
+ `lint` - lint source files and tests,
+ `test` - run tests,
+ `test:watch` - interactive watch mode to automatically re-run tests

## Alternative

As an alternative to TypeScript, you can try my [Node.js Flow boilerplate][flow-boilerplate]. It's basically the same but with ES6, async/await, Flow type checking and ESLint.

## License
Licensed under the APLv2. See the [LICENSE](https://github.com/jsynowiec/node-typescript-boilerplate/blob/master/LICENSE) file for details.

[dependencies-badge]: https://david-dm.org/jsynowiec/node-typescript-boilerplate/dev-status.svg
[dependencies]: https://david-dm.org/jsynowiec/node-typescript-boilerplate?type=dev
[nodejs-badge]: https://img.shields.io/badge/node->=%208.9-blue.svg
[nodejs]: https://nodejs.org/dist/latest-v8.x/docs/api/
[npm-badge]: https://img.shields.io/badge/npm->=%205.5.1-blue.svg
[npm]: https://docs.npmjs.com/
[travis-badge]: https://travis-ci.org/jsynowiec/node-typescript-boilerplate.svg?branch=master
[travis-ci]: https://travis-ci.org/jsynowiec/node-typescript-boilerplate
[typescript]: https://www.typescriptlang.org/
[typescript-29]: https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript#typescript-29
[license-badge]: https://img.shields.io/badge/license-APLv2-blue.svg
[license]: https://github.com/jsynowiec/node-typescript-boilerplate/blob/master/LICENSE
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
[prs]: http://makeapullrequest.com
[donate-badge]: https://img.shields.io/badge/$-support-green.svg
[donate]: http://bit.ly/donate-js
[github-watch-badge]: https://img.shields.io/github/watchers/jsynowiec/node-typescript-boilerplate.svg?style=social
[github-watch]: https://github.com/jsynowiec/node-typescript-boilerplate/watchers
[github-star-badge]: https://img.shields.io/github/stars/jsynowiec/node-typescript-boilerplate.svg?style=social
[github-star]: https://github.com/jsynowiec/node-typescript-boilerplate/stargazers
[twitter]: https://twitter.com/intent/tweet?text=Check%20out%20this%20Node.js%20TypeScript%20boilerplate!%20https://github.com/jsynowiec/node-typescript-boilerplate%20%F0%9F%91%8D
[twitter-badge]: https://img.shields.io/twitter/url/https/jsynowiec/node-typescript-boilerplate.svg?style=social
[jest]: https://facebook.github.io/jest/
[tslint]: https://palantir.github.io/tslint/
[tslint-microsoft-contrib]: https://github.com/Microsoft/tslint-microsoft-contrib
[flow-boilerplate]: https://github.com/jsynowiec/node-flowtype-boilerplate
[wiki-js-tests]: https://github.com/jsynowiec/node-typescript-boilerplate/wiki/Unit-tests-in-plain-JavaScript
