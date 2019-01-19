<h3 align="center">
  <br />
  <img src="https://user-images.githubusercontent.com/168240/41082466-51af365a-69e3-11e8-938d-7c6316f2fc7e.png" alt="logo" width="600" />
  <br />
  <br />
  <br />
</h3>

# go-ethutil

> Ethereum utility functions for Go.

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/miguelmota/go-ethutil/master/LICENSE.md) [![Build Status](https://travis-ci.org/miguelmota/go-ethutil.svg?branch=master)](https://travis-ci.org/miguelmota/go-ethutil) [![Go Report Card](https://goreportcard.com/badge/github.com/miguelmota/go-ethutil?)](https://goreportcard.com/report/github.com/miguelmota/go-ethutil) [![GoDoc](https://godoc.org/github.com/miguelmota/go-ethutil?status.svg)](https://godoc.org/github.com/miguelmota/go-ethutil)

## Documentation

[https://godoc.org/github.com/miguelmota/go-ethutil](https://godoc.org/github.com/miguelmota/go-ethutil)

## Install

```bash
go get -u github.com/miguelmota/go-ethutil
```

## Getting started

```go
package main

import (
	"fmt"
	"log"

	"github.com/miguelmota/go-ethutil"
)

func main() {
	wei := ethutil.ToWei(0.02, 18)
	fmt.Println(wei) // 20000000000000000
}
```

## Examples

Check out the [`./example`](./example) directory and documentation.

## License

MIT
