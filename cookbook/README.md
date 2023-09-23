# Rust Bitcoin Cookbook

Welcome to the `rust-bitcoin` cookbook!
This cookbook is designed to provide readers with a
comprehensive understanding of `rust-bitcoin` and its key features.
Don't forget to check [`rust-bitcoin`'s documentation](https://docs.rs/bitcoin)

## How to contribute

For the cook book we use [`mdbook`](https://rust-lang.github.io/mdBook).
Please check how to install it on your system.

To build the cook book locally, run:

```bash
mdbook build
```

If you want to preview the cook book locally, run:

```bash
mdbook serve
```

Since [`mdbook` does not support external crates](https://github.com/rust-lang/mdBook/issues/706),
we use [`mdbook-keeper`](https://github.com/tfpk/mdbook-keeper/)
to test the code snippets in the cook book.
First, install `mdbook-keeper`:

```bash
cargo install mdbook-keeper
```

Then, run the following command to test the code snippets:

```bash
mdbook test
```
