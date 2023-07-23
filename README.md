iheartperl7 Tutorial Book
=============================

**This books consists of a tutorial and exercises to get you up and running with
the latest features of Perl, including classes, normal subroutines, FP.**

### [Read the Book][book] | [Contributing][contributing]] 

Built by [iheartperl7.com](https://rustwasm.github.io/) with plenty of inspiration
from the books at the rust website especially The Rust and WebAssembly Book


## About

This repository contains the documentation for building the tutorial at iheartperl7.com.  It demos the greatest of Perl's new features with plenty of 
code examples for you to play with.

You can read the book [online here][book].

[*not working yet!!!* Open issues for improving the Rust and WebAssembly book.][book-issues]


## Building the Book

The book is made using [`mdbook`][mdbook]. It assumes you have rust installed. 

You can install the book making software:

```bash
$ cargo install mdbook
```

Now just run this command from this directory:

```bash
$ mdbook build
```

This will build the book and output files into a directory called `book`. From
there you can navigate to the `index.html` file to view it in your browser. You
could also run the following command to automatically generate changes if you
want to look at changes you might be making to it:

```bash
$ mdbook serve --open
```

This will automatically generate the files as you make changes and serves them
locally so you can view them easily without having to call `build` every time.

The files are all written in Markdown and mostly in the `src` directory.

[mdbook]: https://github.com/rust-lang-nursery/mdBook
[rustup]: https://github.com/rust-lang-nursery/rustup.rs/
[book]: https://iheartperl.com/introduction.html
[iheartperl7]: https://iheartperl7.com
