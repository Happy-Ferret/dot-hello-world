# dot-hello-world

[![Build Status](https://travis-ci.org/dpyro/dot-hello-world.svg?branch=master)](https://travis-ci.org/dpyro/dot-hello-world)
[![Dev Dependencies](https://img.shields.io/david/dev/dpyro/dot-hello-world.svg)](https://david-dm.org/dpyro/dot-hello-world)
[![bitHound Overall Score](https://www.bithound.io/github/dpyro/dot-hello-world/badges/score.svg)](https://www.bithound.io/github/dpyro/dot-hello-world)
[![Known Vulnerabilities](https://snyk.io/test/github/dpyro/dot-hello-world/badge.svg)](https://snyk.io/test/github/dpyro/dot-hello-world)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://spdx.org/licenses/MIT.html)

How many config files does it take to build a modern Typescript app?
Let's find out!

## Quickstart

1. Install `gulp`.

    ```shell
    npm install --global gulp
    ```

1. Install dependencies.

    ```shell
    npm install
    ```

1. Build it.

    ```shell
    gulp
    ```

1. Run it.

    ```shell
    node dist/index.js
    ```

    *or*

    ```shell
    npm start
    ```

## Commands

- `gulp`: build
- `gulp watch`: watchify and build TypeScript files
- `gulp lint`
- `gulp test`: build and test
- `gulp doc`: output documentation to `doc/`
- `gulp clean`
- `npm start`: run
- `npm run cover`: stores coverage information in `coverage/`

## IDE Hints

A `launch.json` configuration for VSCode is included.
I also recommend using [QuickTask](https://marketplace.visualstudio.com/items?itemName=lkytal.quicktask) with VSCode: `ext install quicktask`.

## Packages

- [`@types/node`](https://www.npmjs.com/package/@types/node): Gives TypeScript access to node globals such as `require` and `module`.
- [`del`](https://www.npmjs.com/package/del): Allows `gulpfile.js` to delete files.
- [`eslint`](https://www.npmjs.com/package/eslint): JavaScript linter.
- [`gulp`](https://www.npmjs.com/package/gulp): JavaScript task runnner with task dependency management.
- [`gulp-eslint`](https://www.npmjs.com/package/gulp-eslint): Gulp plugin for ESLint.
- [`gulp-imagemin`](https://www.npmjs.com/package/gulp-imagemin): Gulp plugin to minimize images.
- [`gulp-mocha`](https://www.npmjs.com/package/gulp-mocha): Gulp plugin for Mocha.
- [`gulp-tslint`](https://www.npmjs.com/package/gulp-tslint): Gulp plugin for TSLint.
- [`gulp-typedoc`](https://www.npmjs.com/package/typedoc): Gulp plugin for TypeDoc.
- [`gulp-typescript`](https://www.npmjs.com/package/typescript): Gulp plugin for Typescript.
- [`istanbul`](https://www.npmjs.com/package/istanbul): JavaScript code coverage instrumentation library.
- [`mocha`](https://www.npmjs.com/package/mocha): JavaScript test framework.
- [`standard`](https://www.npmjs.com/package/standard): Opinionated JavaScript linting style.
- [`tslint`](https://www.npmjs.com/package/tslint): TypeScript linter.
- [`typedoc`](https://www.npmjs.com/package/typedoc): TypeScript documentation generator.
- [`typescript`](https://www.npmjs.com/package/typescript): Typed JavaScript superset language.
