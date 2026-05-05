# keccak24

> A wrapper for the [`keccak`](https://www.npmjs.com/package/keccak) library to compute 24 bit keccak hash in JavaScript.

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/miguelmota/keccak24/master/LICENSE.md)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## Install

```bash
npm install keccak24
```

### CDN

Available on [jsDelivr](https://www.jsdelivr.com/) CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/keccak24@latest/keccak24.js"></script>
```

## Usage

- **keccak24**(data) -> {Buffer}
  - {String | Buffer} data - data string or Buffer

  Returns a Buffer

## Getting Started

```js
const keccak24 = require('keccak24')

console.log(keccak24('hello').toString('hex')) // "1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8"

console.log(keccak24(Buffer.from('hello')).toString('hex')) // "1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8"
```


## Test

```bash
npm test
```

## License

Released under the [MIT](./LICENSE) license.

© [Miguel Mota](https://github.com/miguelmota)

