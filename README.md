# <img src="http://cdn.tjw.io/images/sails-logo.png" height='43px' /> swagger

[![NPM version][npm-image]][npm-url]
[![Build status][ci-image]][ci-url]
[![Dependency Status][daviddm-image]][daviddm-url]
[![Code Climate][codeclimate-image]][codeclimate-url]

[swagger.io](http://swagger.io/) integration for sails.js.

## Install

```sh
$ npm install sails-swagger --save
```

## Configuration
```js
// config/swagger.js
var SailsSwagger = require('sails-swagger/util');
module.exports.swagger = {
  schema: {
    swagger: '2.0',
    info: SailsSwagger.getInfo(require('../package'))
  }
};
```

## License
MIT

## Maintained By
##### [<img src='http://i.imgur.com/zM0ynQk.jpg' height='34px'>](http://balderdash.co)

[npm-image]: https://img.shields.io/npm/v/sails-swagger.svg?style=flat-square
[npm-url]: https://npmjs.org/package/sails-swagger
[ci-image]: https://img.shields.io/travis/tjwebb/sails-swagger/master.svg?style=flat-square
[ci-url]: https://travis-ci.org/tjwebb/sails-swagger
[daviddm-image]: http://img.shields.io/david/tjwebb/sails-swagger.svg?style=flat-square
[daviddm-url]: https://david-dm.org/tjwebb/sails-swagger
[codeclimate-image]: https://img.shields.io/codeclimate/github/tjwebb/sails-swagger.svg?style=flat-square
[codeclimate-url]: https://codeclimate.com/github/tjwebb/sails-swagger
