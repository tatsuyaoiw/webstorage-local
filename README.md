# webstorage-local

[![Build Status](https://travis-ci.org/tatsuyaoiw/webstorage-local.svg?branch=master)](https://travis-ci.org/tatsuyaoiw/webstorage-local)

A [webstorage] persistence plugin for local file storage.

## Installation

```
$ npm install webstorage-local
```

## Usage

Pass directory name where data stored in. Then you can add it to [webstorage] constructor.

```js
var webstorage = require('webstorage');
var local = require('webstorage-local');

webstorage(local('/tmp'));
```

## License

MIT

[webstorage]: https://github.com/tatsuyaoiw/webstorage
