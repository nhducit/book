# The Rust Programming Language Book [![Build Status](https://travis-ci.org/rust-vietnam/book.svg?branch=master)](https://travis-ci.org/rust-vietnam/book)

## Requirements
Install rust
An easy way to install the stable Rust binaries for Linux and Mac is to run this in your shell:
```
curl -sSf https://static.rust-lang.org/rustup.sh | sh
```
For windows: 
```
https://www.rust-lang.org/en-US/downloads.html
```


Building book require [mdBook](https://github.com/azerupi/mdBook) >= v0.0.13. To
get it:

```
cargo install mdbook
```

## Building

```
mdbook build
```

The output will be in the book directory. To check it out, open it in your
browser:

```
open -a "Firefox" book/index.html # OS X
```

```
open -a "Google Chrome" book/index.html # OS X
```

To run the tests:

```
mdbook test
```

## Contributing
