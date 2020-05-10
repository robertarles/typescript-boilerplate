# typescript-boilerplate

## New project template

+ [TypeScript][typescript] [3.8][typescript-38]
+ [ESLint][eslint] with some initial rules recommendation
+ [Mocha/Chai/Sinon][?] for unit testing, assertions, and mocking
+ Type definitions for Node.js
+ [Prettier][prettier] to enforce consistent code style
+ NPM [scripts](#available-scripts) for common operations
+ simple example of TypeScript code and unit test
+ example configuration for [GitHub Actions][gh-actions]

## Use as a repository template

To start, just click the **[Use template][repo-template-action]** link (or the green button). Now start adding your code in the `src` and unit tests in the `__tests__` directories.

## Available Scripts

+ `clean` - remove coverage data, Jest cache and transpiled files,
+ `build` - transpile TypeScript to ES6,
+ `build:watch` - interactive watch mode to automatically transpile source files,
+ `lint` - lint source files and tests,
+ `test` - run tests,
+ `test:watch` - interactive watch mode to automatically re-run tests

[eslint]: https://github.com/eslint/eslint
[wiki-js-tests]: https://github.com/jsynowiec/node-typescript-boilerplate/wiki/Unit-tests-in-plain-JavaScript
[prettier]: https://prettier.io
[gh-actions]: https://github.com/features/actions
[travis]: https://travis-ci.org

[repo-template-action]: https://github.com/jsynowiec/node-typescript-boilerplate/generate
