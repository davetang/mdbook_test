# mdBook

Install.

```console
cargo install mdbook
```

New book.

```console
mdbook init my-first-book
cd my-first-book
mdbook build
```

## Examples

[The Rust Programming Language](https://github.com/rust-lang/book) is prepared
using `mdbook`, so take a look at the source to see how things are done! For
example all code snippets are stored separately in `cargo` initialised
directories and are included using the following syntax:

```rust
{{#rustdoc_include ../listings/ch08-common-collections/listing-08-20/src/main.rs:here}}
```

See [Configuring
Preprocessors](https://rust-lang.github.io/mdBook/format/configuration/preprocessors.html?highlight=rustdoc_include#configuring-preprocessors).
