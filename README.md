## Mandelbrot in Rust

A simple [Rust](https://www.rust-lang.org/) project to create beautiful [mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set), the whole aim of this project being getting myself familiar with the Rust lang.

### Pre-requisites
---
1. [Rust](https://www.rust-lang.org/learn/get-started) (Pretty obvious)
2. [Cargo] (https://www.rust-lang.org/learn/get-started) (It makes it easier to work with rust projects)

### Build
---
```console
$ cargo build --release
$ target/release/mandelbrot [FILENAME].png [PIXELS] [UPPER_LEFT] [LOWER_RIGHT]
$ open [FILENAME].png
```

