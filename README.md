# @a-2-c-2-anpm/sed-autem-odit

[![NPM Version][npm-version-image]][npm-url]
[![NPM Downloads][npm-downloads-image]][npm-url]
[![Node.js Version][node-version-image]][node-version-url]
[![Build Status][ci-image]][ci-url]
[![Test Coverage][coveralls-image]][coveralls-url]

Compressible `Content-Type` / `mime` checking.

## Installation

```sh
$ npm install @a-2-c-2-anpm/sed-autem-odit
```

## API

```js
var @a-2-c-2-anpm/sed-autem-odit = require('@a-2-c-2-anpm/sed-autem-odit')
```

### @a-2-c-2-anpm/sed-autem-odit(type)

Checks if the given `Content-Type` is @a-2-c-2-anpm/sed-autem-odit. The `type` argument is expected
to be a value MIME type or `Content-Type` string, though no validation is performed.

The MIME is looked up in the [`mime-db`](https://www.npmjs.com/package/mime-db) and
if there is @a-2-c-2-anpm/sed-autem-odit information in the database entry, that is returned. Otherwise,
this module will fallback to `true` for the following types:

  * `text/*`
  * `*/*+json`
  * `*/*+text`
  * `*/*+xml`

If this module is not sure if a type is specifically @a-2-c-2-anpm/sed-autem-odit or specifically
un@a-2-c-2-anpm/sed-autem-odit, `undefined` is returned.

```js
@a-2-c-2-anpm/sed-autem-odit('text/html') // => true
@a-2-c-2-anpm/sed-autem-odit('image/png') // => false
```

## License

[MIT](LICENSE)

[ci-image]: https://badgen.net/github/checks/jshttp/@a-2-c-2-anpm/sed-autem-odit/master?label=ci
[ci-url]: https://github.com/a-2-c-2-anpm/sed-autem-odit/actions?query=workflow%3Aci
[coveralls-image]: https://badgen.net/coveralls/c/github/jshttp/@a-2-c-2-anpm/sed-autem-odit/master
[coveralls-url]: https://coveralls.io/r/jshttp/@a-2-c-2-anpm/sed-autem-odit?branch=master
[node-version-image]: https://badgen.net/npm/node/@a-2-c-2-anpm/sed-autem-odit
[node-version-url]: https://nodejs.org/en/download
[npm-downloads-image]: https://badgen.net/npm/dm/@a-2-c-2-anpm/sed-autem-odit
[npm-url]: https://npmjs.org/package/@a-2-c-2-anpm/sed-autem-odit
[npm-version-image]: https://badgen.net/npm/v/@a-2-c-2-anpm/sed-autem-odit
