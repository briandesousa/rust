# Rust Playground with Codespaces

This project is based on the generic starter for developers to use in Codespaces that includes basic system tools and extensions required for Rust development.

## What's Included

This is a basic environment that should be ready to expand upon to build a day-to-day development envrionment for Rust. It comes with the following software choices:

### System Tools

- [curl/curl](https://github.com/curl/curl): the command line tool for transferring data over a metric boatload of protocols.
- git: the Git SCM tool.
- [gnupg2](https://gnupg.org/): a complete and free implementatiuon of the OpenPGP standard.
- [stedolan/jq](https://github.com/stedolan/jq) - a command line JSON parser.
- [sudo](https://www.sudo.ws/) - the superuser authority delegation tool.
- [zsh](https://www.zsh.org/) - interactive terminal (alternative to `bash`).
- [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) - a delightful community driven framework for managing zsh config.
- [vim](https://www.vim.org/) - a text editor
- build essentials - tools for compiling and linking code
- [openssl](https://www.openssl.org/) - tls and ssl toolkit

### Rust Tools

Besides Rust and Cargo, the image comes with the following Rust related tooling:

- [rustup](https://rustup.rs/): installer and toolchain manager
- [rustfmt](https://github.com/rust-lang/rustfmt): a tool for formatting Rust code according to style guidelines
- [clippy](https://github.com/rust-lang/rust-clippy): lints to catch common mistakes and improve your Rust code

### VS Code Extensions

- [Rust Analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer): an alternative rust language server to the RLS.
- [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb): native debugger based on LLDB.
- [Crates](https://marketplace.visualstudio.com/items?itemName=serayuzgur.crates): helps Rust developers managing dependencies with Cargo.toml.
- [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare): collaborative, multi-user remote editing from directly within the editor.

### Operating System

- [Ubuntu 18.04](https://releases.ubuntu.com/18.04.4/): The 18.04 LTS version of Ubuntu.

## Usage

### Rust

* Create a project using `cargo new`.
* Build a project using `cargo build`.
* Build and run a project in one step using `cargo run`.
* Build a project without producing a binary to check for errors using `cargo check`. Instead of saving the result of the build in the same directory as our code, Cargo stores it in the target/debug directory.
* Create a release build using `cargo build --release`.