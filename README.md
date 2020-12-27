# rs-workspaces

Note that the Cargo.toml file was initially created by hand.
You need to manually add the projects (crate names) to the 'members' field in the top-level `Cargo.Toml`.
Then just use `cargo new --lib` and `cargo new --bin`  as required.

See http://web.mit.edu/rust-lang_v1.25/arch/amd64_ubuntu1404/share/doc/rust/html/book/second-edition/ch14-03-cargo-workspaces.html

You can even have multiple binaries. Just use the following when running:

```
c run --bin somebin
```

or

```
c run --bin anotherbin
```
