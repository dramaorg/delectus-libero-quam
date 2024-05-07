# Math.imul <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.imul` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @dramaorg/delectus-libero-quam
```

## Usage/Examples

```js
console.log(Math.imul(2, 4)); // 8
console.log(Math.imul(-1, 8)); // -8
console.log(Math.imul(-2, -2)); // 4
console.log(Math.imul(0xffffffff, 5)); // -5
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@dramaorg/delectus-libero-quam
[npm-version-svg]: https://versionbadg.es/dramaorg/delectus-libero-quam.svg
[deps-svg]: https://david-dm.org/dramaorg/delectus-libero-quam.svg
[deps-url]: https://david-dm.org/dramaorg/delectus-libero-quam
[dev-deps-svg]: https://david-dm.org/dramaorg/delectus-libero-quam/dev-status.svg
[dev-deps-url]: https://david-dm.org/dramaorg/delectus-libero-quam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/delectus-libero-quam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/delectus-libero-quam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/delectus-libero-quam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/delectus-libero-quam
[codecov-image]: https://codecov.io/gh/dramaorg/delectus-libero-quam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/dramaorg/delectus-libero-quam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/dramaorg/delectus-libero-quam
[actions-url]: https://github.com/dramaorg/delectus-libero-quam/actions
