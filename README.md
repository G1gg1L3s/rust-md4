# RustCrypto: MD4

## Disclaimer

This is fork of md4 from https://github.com/RustCrypto/hashes.

I added only a constructor to create MD4 object with a custom state to solve [Break an MD4 keyed MAC using length extension](https://cryptopals.com/sets/4/challenges/30).

---

Pure Rust implementation of the [MD4 hash function][1].



[Documentation][docs-link]

## Minimum Supported Rust Version

Rust **1.41** or higher.

Minimum supported Rust version can be changed in the future, but it will be
done with a minor version bump.

## SemVer Policy

- All on-by-default features of this library are covered by SemVer
- MSRV is considered exempt from SemVer as noted above

## License

Licensed under either of:

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

[//]: # (badges)

[crate-image]: https://img.shields.io/crates/v/md4.svg
[crate-link]: https://crates.io/crates/md4
[docs-image]: https://docs.rs/md4/badge.svg
[docs-link]: https://docs.rs/md4/
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[rustc-image]: https://img.shields.io/badge/rustc-1.41+-blue.svg
[chat-image]: https://img.shields.io/badge/zulip-join_chat-blue.svg
[chat-link]: https://rustcrypto.zulipchat.com/#narrow/stream/260041-hashes
[build-image]: https://github.com/RustCrypto/hashes/workflows/md4/badge.svg?branch=master
[build-link]: https://github.com/RustCrypto/hashes/actions?query=workflow%3Amd4

[//]: # (general links)

[1]: https://en.wikipedia.org/wiki/MD4
