Redigo
======

[![Build Status](https://travis-ci.org/quentinlesceller/redigo.svg?branch=master)](https://travis-ci.org/quentinlesceller/redigo)
[![GoDoc](https://godoc.org/github.com/quentinlesceller/redigo/redis?status.svg)](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis)

Redigo is a [Go](http://golang.org/) client for the [Redis](http://redis.io/) database.

Features
-------

* A [Print-like](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#hdr-Executing_Commands) API with support for all Redis commands.
* [Pipelining](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#hdr-Pipelining), including pipelined transactions.
* [Publish/Subscribe](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#hdr-Publish_and_Subscribe).
* [Connection pooling](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#Pool).
* [Script helper type](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#Script) with optimistic use of EVALSHA.
* [Helper functions](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#hdr-Reply_Helpers) for working with command replies.

Documentation
-------------

- [API Reference](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis)
- [FAQ](https://github.com/quentinlesceller/redigo/wiki/FAQ)
- [Examples](https://pkg.go.dev/github.com/quentinlesceller/redigo/redis#pkg-examples)

Installation
------------

Install Redigo using the "go get" command:

    go get github.com/quentinlesceller/redigo/redis

The Go distribution is Redigo's only dependency.

Related Projects
----------------

- [rafaeljusto/redigomock](https://pkg.go.dev/github.com/rafaeljusto/redigomock) - A mock library for Redigo.
- [chasex/redis-go-cluster](https://github.com/chasex/redis-go-cluster) - A Redis cluster client implementation.
- [FZambia/sentinel](https://github.com/FZambia/sentinel) - Redis Sentinel support for Redigo
- [mna/redisc](https://github.com/mna/redisc) - Redis Cluster client built on top of Redigo

Contributing
------------

See [CONTRIBUTING.md](https://github.com/quentinlesceller/redigo/blob/master/.github/CONTRIBUTING.md).

License
-------

Redigo is available under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
