# libpnet [![Build Status](https://travis-ci.org/libpnet/libpnet.svg)](https://travis-ci.org/libpnet/libpnet)

`libpnet` provides a cross-platform API for low level networking using Rust.

There are three key components:

 * The packet module, allowing safe construction and manipulation of packets
 * The transport module, which allows implementation of transport protocols
 * The datalink module, which allows sending and receiving data link packets directly

# Documentation

API documentation for the lastest build can be found here: http://octarineparrot.com/assets/libpnet/doc/pnet/.

# Support

Find us on IRC in [#libpnet on freenode](http://webchat.freenode.net/?channels=%23libpnet), or [#rust on irc.mozilla.org](http://chat.mibbit.com/?server=irc.mozilla.org&channel=%23rust).

# Usage

To use `libpnet` in your project, add the following to your Cargo.toml:

```
[dependencies.pnet]
git = "https://github.com/libpnet/libpnet.git"
```

When developing, use the provided Makefile, which does weird things to make the
tests work properly.
