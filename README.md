PHP-Isbn
=====================
[![Build Status](https://travis-ci.org/Wooble/php-isbn.svg)](https://travis-ci.org/Wooble/php-isbn)
[![Coverage Status](https://img.shields.io/coveralls/Wooble/php-isbn.svg)](https://coveralls.io/r/Wooble/php-isbn)

- Author: Mike White (<m@mwhite.info>)
- License: MIT License

PHP-Isbn is a simple class that provides methods for validating and converting
between 10- and 13-digit ISBNs with a full test suite that includes some more
unusual scenarios.

Be mindful of the fact that sometimes books are published with numerically
invalid ISBNs due to typos, but these sometimes become official ISBNs. On the
other hand, many numerically valid ISBNs exist that don't correspond to any
book.

Support for hyphenating ISBNs is not included because it requires querying
stored data about the meaning of parts of an ISBN. For that functionality, see,
for example, [this library](https://github.com/davemontalvo/ISBN-Tools).
