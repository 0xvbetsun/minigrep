# Mini Grep

[![CI](https://github.com/vbetsun/minigrep/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/vbetsun/minigrep/actions/workflows/ci.yml)

Project from [Rust Book](https://doc.rust-lang.org/book/ch12-00-an-io-project.html) which makes a light weight version of the `grep` (**g**lobally search a **r**egular **e**xpression and **p**rint) tool

## Usage


```sh
# Case Sensitive (ignores letter case)
cargo run -- searchstring example-filename.txt

# Case Insensitive
## 1. shell
IGNORE_CASE=1 cargo run -- searchstring example-filename.txt

## 2. windows Powershell
$Env:IGNORE_CASE=1; cargo run -- searchstring example-filename.txt
```

## Test

Run:

```sh
cargo test
```