# Mini Grep

![CI](https://github.com/vbetsun/minigrep/workflows/CI/badge.svg)

Project from [Rust Book](https://doc.rust-lang.org/book/ch12-00-an-io-project.html) which makes a light weight version of the `grep` (**g**lobally search a **r**egular **e**xpression and **p**rint) tool

## How To Use

### Case Sensitive
```sh
cargo run -- searchstring example-filename.txt
```

### Case Insensitive

```sh
# shell
IGNORE_CASE=1 cargo run -- searchstring example-filename.txt

# windows
$Env:IGNORE_CASE=1; cargo run -- searchstring example-filename.txt
```

## How to Test

Run:

```sh
cargo test
```
