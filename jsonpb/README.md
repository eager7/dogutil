jsonpb
=====

[![Build Status](https://travis-ci.org/eager7/dogutil.svg?branch=master)](https://travis-ci.org/eager7/dogutil)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/eager7/dogutil/bloom)

Package jsonpb provides an API for marshaling protobuf objects to JSON and back. There is a golang library
to perform these operations, however it converts all byte arrays to base64 strings instead of hex which is 
typically used by Bitcoin Cash. It also doesn't know to convert little endian byte arrays to big endian.

Thus this package is a wrapper around the original jsonpb package that handles marshaling and unmarshaling
to the format expected in Bitcoin Cash.

## Installation and Updating

```bash
$ go get -u github.com/eager7/dogutil/jsonpb
```

## License

Package jsonpb is licensed under the [copyfree](http://copyfree.org) ISC
License.
