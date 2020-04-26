merkleblock
=====

[![Build Status](https://travis-ci.org/eager7/dogutil.svg?branch=master)](https://travis-ci.org/eager7/dogutil)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/eager7/dogutil/bloom)

Package merkleblock provides an API for creating and validating SPV proofs. An SPV proof
is a cryptographic proof that a given transaction is contained in the block. Instead of the
prover providing the full block he can provide the much smaller SPV proof.

## Installation and Updating

```bash
$ go get -u github.com/eager7/dogutil/merkleblock
```

## License

Package merkleblock is licensed under the [copyfree](http://copyfree.org) ISC
License.
