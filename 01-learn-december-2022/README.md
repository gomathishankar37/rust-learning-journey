# 01-learn-december-2022
[Rust Book - Steve Klabnik & Carol Nichols](https://doc.rust-lang.org/book/title-page.html) | [Tom McGurl](https://www.youtube.com/@TomMcGurl)

## Installation
- Rust Installer Script - `$ curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh` 
- Check installation & version - `rustc --version`
- Update rust - `rustup update`
- Uninstall - `rustup self uninstall`
- Online [Rust Playground](https://play.rust-lang.org/)

## ToolChains
- rustup: Rust lang toolchain installer
- rls (Rust Language Server): Provides a server to run rust in background
- rust-src: build-dependency to download rust source code tarball, associated with `rustc`
- rust-analyzer: Modular compiler frontend, supports IDE. Also known as rls-2.0
- cargo: Rust lang Package manager. Downloads, Compiles, Distributes and publishes packages to [crates.io](https://crates.io/), a Rust Community Package Registry
- clippy: A collection of lints to catch common mistakes in rust-lang
- rust-docs: Rust Lang Documentation `rustup doc`
- rust-std: Rust standard library, with a set of minimal and battle tested utilities and functions.
- rustc: Rust Compiler. Does `src code -> binary code (as lib or exe)`
