# Chapter 1 - Getting Started

## Installing rustup on Linux or macOS

- Open the terminal and run the following command
  - `curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh`

## Installing rustup on Windows

- Browse to the following URL for instructions to install rustup on Windows
  - https://www.rust-lang.org/tools/install

## Check Rust version

- `rustc --version`

## Update Rust

- `rustup update`

## Uninstall Rust

- `rustup self uninstall`

## Compiling a Rust program - Mac/Linux

Before running a Rust program, it needs to be compiled

- `rustc main.rs`
- `./main`

## Compiling a Rust program - Windows

Before running a Rust program, it needs to be compiled

- `rustc main.rs`
- `.\main`

## Cargo

Cargo is Rust's build system
Checking if cargo is installed

- `cargo --version`

If cargo is installed, a version number will be returned. If `command not found` is returned, check the documentation to install cargo

## Creating a new project with Cargo

- `cargo new <project name>`

## Cargo configuration

- `Cargo.toml`
  - `[package]`
  - `name = "hello_cargo"`
  - `version = "0.1.0"`
  - `edition = "2021"`
- More keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

## Building a cargo project

- `cargo build`

## Running a cargo project

- `cargo run`

## Checking if code compiles but does not create an executable

- `cargo check`

## Building for release

- `cargo build --release`

