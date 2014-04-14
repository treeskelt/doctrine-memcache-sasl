# MemcacheSASL

A pure PHP Memcache client with [binary
protocol](http://code.google.com/p/memcached/wiki/BinaryProtocolRevamped)
and [SASL](http://code.google.com/p/memcached/wiki/SASLAuthProtocol)
support.

It aims to be compatible with the PHP Memcached class. You can find
documentation on the PHP Memcached class
[here](http://php.net/manual/en/class.memcached.php). Not all features
are supported at this time.

## Changes vs. ronnywang Version

This is a fork of the original code base by [Ronny
Wang](https://github.com/ronnywang/PHPMemcacheSASL). We have made the
following improvements:

* Support for `flush`.
* Support for timeouts on operations (connections and requests).
* Fixed `increment` and `decrement` operations.
* Support for the PHP Composer package manager.

## Licensing

This library is BSD-licensed.

## Get involved!

We are happy to receive bug reports, fixes, documentation enhancements,
and other improvements.

Please report bugs via the
[github issue tracker](http://github.com/memcachier/PHPMemcacheSASL/issues).

Master [git repository](http://github.com/memcachier/PHPMemcacheSASL):

* `git clone git://github.com/memcachier/PHPMemcacheSASL.git`

## Authors

This library was written by [Ronny
Wang](https://github.com/ronnywang/PHPMemcacheSASL) and MemCachier.

Ronny Wang wrote the initial version and bulk of the code, MemCachier
later forked it to improve on the code base.

