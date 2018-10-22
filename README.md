# High-Level, Rust-y Bindings for the ENet library

This crate aims to provide high-level, rust-y bindings for the ENet library.
ENet is a networking library for games that builds on UDP,
offering optional reliability, congestion control, connection-orientation and
other related features. For more information, check out the
[ENet Website](http://enet.bespin.org).

## Status

For now, this library is **alpha**. It builds on the C-bindings for ENet,
the [enet-sys crate](https://github.com/ruabmbua/enet-sys). A lot of the
functionality is there, but not everything. Also, since ENet has
pretty unclear lifetime semantics, you might actually run into cases where
things crash. **In those cases, or when something is missing/not yet in the API,
open a bug report, and I will look into it as soon as possible.**

## Usage

Not yet on crates.io. For now, use:

```toml
[dependencies]
enet = { git = "https://github.com/futile/enet-rs.git" }
```

## Documentation & Examples

Documentation is available by running `cargo doc`. An example server and client
can be found in the `examples` directory.

## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
