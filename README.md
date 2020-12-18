Not _Yet_ Awesome PureScript
===

An unofficial list of things that are _not yet_ awesome in PureScript. Please add any other items to this list, so we can be sure to tackle everything necessary to make PureScript _totally_ awesome! Inspired by [Not-Yet-Awesome Rust](https://github.com/not-yet-awesome-rust/not-yet-awesome-rust).

### Tooling

#### IDE

There are a few minor missing features such as:
- Autocompletion of record fields 
- For functions and values defined within a `let` or `where` block:
    - Go to definition
    - Type signature on hover

#### Formatter

Some commonly-mentioned issues with purty are:
- [Unwanted newlines between repeated declarations](https://gitlab.com/joneshf/purty/-/issues/77)

### Optimizations

There are a few ongoing efforts to reduce code size and improve performance.

Todo - add some links

### New user experience

It can be pretty tough to get started and build that first web app, especially for folks without much FP or Web dev experience. There are also a wide variety of web frameworks to choose from, which can be overwhelming for new users.

### Packages

- Currently transitioning to a new [registry](https://github.com/purescript/registry).
- Many core libraries could use some additional explanation and examples.
- CI gaps:
    - No widespread use of [doctest](https://github.com/csicar/purescript-doctest) (or equivalent - see Pyhon's [doctest](https://docs.python.org/3/library/doctest.html)).
    - No framework for catching performance regressions (e.g. Julia's [PkgBenchmark](https://github.com/JuliaCI/PkgBenchmark.jl)).
