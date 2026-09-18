# Contributing

libpostproject is in its initial design phase. Discuss changes with lasting ABI
or schema consequences before implementation. Keep each change focused and add
tests and documentation alongside behavior.

Before submitting a change, run:

```sh
cargo fmt --check
cargo clippy --workspace --all-targets --all-features -- -D warnings
cargo test --workspace --all-features
cargo doc --workspace --all-features --no-deps
```

Use conventional, imperative commit subjects. Do not commit generated build
artifacts or real production media.

