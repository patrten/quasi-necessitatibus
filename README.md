# @patrten/quasi-necessitatibus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Set` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-set-objects).

## Getting started

```sh
npm install --save @patrten/quasi-necessitatibus
```

## Usage/Examples

```js
var set = new Set();
var obj = {};

set.add(obj);

set.has(obj); // true
map.has(3); // false
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/patrten/quasi-necessitatibus
[npm-version-svg]: https://versionbadg.es/patrten/quasi-necessitatibus.svg
[deps-svg]: https://david-dm.org/patrten/quasi-necessitatibus.svg
[deps-url]: https://david-dm.org/patrten/quasi-necessitatibus
[dev-deps-svg]: https://david-dm.org/patrten/quasi-necessitatibus/dev-status.svg
[dev-deps-url]: https://david-dm.org/patrten/quasi-necessitatibus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrten/quasi-necessitatibus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrten/quasi-necessitatibus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrten/quasi-necessitatibus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrten/quasi-necessitatibus
[codecov-image]: https://codecov.io/gh/patrten/quasi-necessitatibus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/patrten/quasi-necessitatibus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/patrten/quasi-necessitatibus
[actions-url]: https://github.com/patrten/quasi-necessitatibus/actions
