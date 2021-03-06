MAX UINT16
===
[![NPM version][npm-image]][npm-url] [![Build Status][build-image]][build-url] [![Coverage Status][coverage-image]][coverage-url] [![Dependencies][dependencies-image]][dependencies-url]

> Maximum unsigned 16-bit integer.


## Installation

``` bash
$ npm install const-max-uint16
```


## Usage

``` javascript
var MAX_UINT16 = require( 'const-max-uint16' );
```

#### MAX_UINT16

Maximum unsigned 16-bit integer.

``` javascript
MAX_UINT16 === Math.pow( 2, 16 ) - 1;
```


## Examples

``` javascript
var MAX_UINT16 = require( 'const-max-uint16' );

console.log( MAX_UINT16 );
// returns 65535
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


---
## Tests

### Unit

This repository uses [tape][tape] for unit tests. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul][istanbul] as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


### Browser Support

This repository uses [Testling][testling] for browser testing. To run the tests in a (headless) local web browser, execute the following command in the top-level application directory:

``` bash
$ make test-browsers
```

To view the tests in a local web browser,

``` bash
$ make view-browser-tests
```

<!-- [![browser support][browsers-image]][browsers-url] -->


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015-2016. The [Compute.io][compute-io] Authors.


[npm-image]: http://img.shields.io/npm/v/const-max-uint16.svg
[npm-url]: https://npmjs.org/package/const-max-uint16

[build-image]: http://img.shields.io/travis/const-io/max-uint16/master.svg
[build-url]: https://travis-ci.org/const-io/max-uint16

[coverage-image]: https://img.shields.io/codecov/c/github/const-io/max-uint16/master.svg
[coverage-url]: https://codecov.io/github/const-io/max-uint16?branch=master

[dependencies-image]: http://img.shields.io/david/const-io/max-uint16.svg
[dependencies-url]: https://david-dm.org/const-io/max-uint16

[dev-dependencies-image]: http://img.shields.io/david/dev/const-io/max-uint16.svg
[dev-dependencies-url]: https://david-dm.org/dev/const-io/max-uint16

[github-issues-image]: http://img.shields.io/github/issues/const-io/max-uint16.svg
[github-issues-url]: https://github.com/const-io/max-uint16/issues

[tape]: https://github.com/substack/tape
[istanbul]: https://github.com/gotwarlost/istanbul
[testling]: https://ci.testling.com

[compute-io]: https://github.com/compute-io
