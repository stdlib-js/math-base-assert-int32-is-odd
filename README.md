<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isOdd

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Test if a 32-bit integer is odd.

<section class="installation">

## Installation

```bash
npm install @stdlib/math-base-assert-int32-is-odd
```

</section>

<section class="usage">

## Usage

```javascript
var isOdd = require( '@stdlib/math-base-assert-int32-is-odd' );
```

#### isOdd( x )

Tests if 32-bit integer is odd.

```javascript
var bool = isOdd( 5 );
// returns true

bool = isOdd( -2 );
// returns false

bool = isOdd( 0 );
// returns false
```

</section>

<!-- /.usage -->

<section class="notes">

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var randu = require( '@stdlib/random-base-randu' );
var round = require( '@stdlib/math-base-special-round' );
var isOdd = require( '@stdlib/math-base-assert-int32-is-odd' );

var bool;
var x;
var i;

for ( i = 0; i < 100; i++ ) {
    x = round( randu()*100.0 );
    bool = isOdd( x );
    console.log( '%d is %s', x, ( bool ) ? 'odd' : 'not odd' );
}
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/math-base-assert-int32-is-odd.svg
[npm-url]: https://npmjs.org/package/@stdlib/math-base-assert-int32-is-odd

[test-image]: https://github.com/stdlib-js/math-base-assert-int32-is-odd/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/math-base-assert-int32-is-odd/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/math-base-assert-int32-is-odd/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/math-base-assert-int32-is-odd?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/math-base-assert-int32-is-odd.svg
[dependencies-url]: https://david-dm.org/stdlib-js/math-base-assert-int32-is-odd/main

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/math-base-assert-int32-is-odd/main/LICENSE

</section>

<!-- /.links -->
