# go-charset/charset

[![Build Status](https://travis-ci.org/mantyr/go-charset/charset.svg?branch=master)](https://travis-ci.org/mantyr/go-charset/charset/) [![GoDoc](https://godoc.org/github.com/mantyr/go-charset/charset?status.png)](http://godoc.org/github.com/mantyr/go-charset/charset/)

The charset package implements translation between character sets. It uses Unicode as the intermediate representation. Because it can be large, the character set data is separated from the charset package. It can be embedded in the Go executable by importing the data package:

    import _ "github.com/mantyr/go-charset/data"

It can also made available in a data directory (by settting CharsetDir).


## Installation

    $ go get github.com/mantyr/go-charset/charset


[mantyr]: https://github.com/mantyr
