### Hi there 👋

I'm passionate about [Rust](https://www.rust-lang.org/), amongst other things.

### Projects

- [diff.rs](https://diff.rs): Web application to render a diff between Rust crate versions. Written in WebAssembly using the Yew framework, fully static.
- [Cindy](https://cindy.pics): Tool and Web application used to categorize and label media files, for use in machine learning. Uses `ffmpeg` to get file metadata and has custom query engine to filter results.
- [Passgen](https://passgen.it): Password generator that can generate a random password matching a regex. Supports reading word lists to generate [XKCD936](https://xkcd.com/936/)-style passwords. Supports building markov chain of letter sequences to generate higher-entropy, pronounceable words for any language.

### Rust Crates

- [imstr](https://github.com/xfbs/imstr): Cheaply clonable and slicable UTF-8 strings.
- [restless](https://github.com/xfbs/restless): Define your REST API statically using the Rust trait system.
- [amqp-value-json](https://docs.rs/amqp-value-json/0.1.0/amqp_value_json/): Conversions between AMQP values and JSON values, useful to turn JSON data into AMQP message header to make it easy to filter based on the JSON fields.
- [wireguard-keys](https://crates.io/crates/wireguard-keys): Crate to generate, parse, serialize and deserialize Wireguard (x25519) keys.
- [macrodb](https://github.com/xfbs/macrodb): Lightweight macro-generated in-memory database in Rust. Supports indices and is generic over the underlying data structures.
- [wasm-cache](https://github.com/xfbs/wasm-cache): In-memory request cache with invalidation logic for Rust WebAssembly applications.

### Writing

- [Primer on file system APIs and quirks](https://github.com/xfbs/fsdoc/releases/download/v2019-10-06/fsdoc.pdf)
- [Building a toy DNS server in Rust](https://github.com/xfbs/dnsfun)
- [Why I think AsyncRead is not well-designed](https://xfbs.net/posts/2023-05-07-tokio-bug/)
