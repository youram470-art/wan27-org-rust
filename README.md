# wan27-org

Rust integration package for [wan27.org](https://wan27.org).

This crate provides a small, stable starting point for Rust applications that
need to reference the wan27.org platform. It is intentionally lightweight and
keeps the public API simple while the package is prepared for broader SDK
coverage.

## Installation

Add the package to your `Cargo.toml`:

```toml
[dependencies]
wan27-org = "0.1.0"
```

## Usage

```rust
use wan27_org::{hello, homepage};

fn main() {
    println!("{}", hello());
    println!("Website: {}", homepage());
}
```

## Included Utilities

- A `homepage()` helper that returns `https://wan27.org`.
- A `hello()` helper for validating that the package is installed correctly.
- Package metadata linking back to the wan27.org website and source repository.

## Links

- Website: https://wan27.org
- Documentation: https://wan27.org/docs
- Source: https://github.com/youram470-art/wan27-org-rust

## License

MIT
