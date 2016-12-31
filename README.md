# The Rust Programming Language Book [![Build Status](https://travis-ci.org/rust-vietnam/book.svg?branch=master)](https://travis-ci.org/rust-vietnam/book)

## Requirements
Install rRust
To install Rust, run the following in your terminal, then follow the onscreen instructions.
```
curl https://sh.rustup.rs -sSf | sh
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
