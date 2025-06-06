# Tracker

[![License](https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square)](LICENSE-APACHE)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE-MIT)

## About

Track the fulfillment of time-critical responsibilities and promises in your terminal.

Track serves as a convenient and easy-to-use tracking tool to monitor if other parties respect the
due dates for delivery or task completion that was agreed upon. The application is operated via an
intuitive terminal user interface (TUI).

## Installation

For the time being, you must have [Rust](https://www.rust-lang.org/) installed on your machine.
To install Rust, it's recommended to follow
[Rust's installation instructions](https://www.rust-lang.org/tools/install) for your respective
operating system.

Afterward, you can install `tracker` by running `cargo install tracker`.

## Usage

Tracker's graphical command-line interface is invoked with the following command:

`tracker`

For further information run `tracker --help`.

## Development

After checking out the repo, run `cargo check` followed by `cargo build` to install dependencies.
Then, run `cargo test` to run the tests. You can also run `cargo run` to open the tracker and play
around with the widgets that are available.

If you work on new features, you should also add the proper documentation. Please run `cargo doc`
before you create a pull request and especially before you publish. To release a new version,
update the version number in [Cargo.toml](Cargo.toml), and then run `cargo publish`, which will
upload the package to [crates.io](https://crates.io). The project adheres to the
[semantic versioning](https://semver.org/) standard.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/gitkeeper/tracker. This
project is intended to be a safe, welcoming space for collaboration, and contributors are expected
to adhere to the [code of conduct](CODE_OF_CONDUCT.md).

## License

This package is available as open source and dual-licensed under the terms of
[Apache 2.0](LICENSE-APACHE) and [MIT](LICENSE-MIT). The user or developer choosing to use,
distribute, or modify this software can opt to do so under either of these licenses, adhering to
the terms and conditions defined by the license they choose.
