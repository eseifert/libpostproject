# Testing

The required local quality gate is:

```sh
cargo fmt --check
cargo clippy --workspace --all-targets --all-features -- -D warnings
cargo test --workspace --all-features
cargo doc --workspace --all-features --no-deps
```

Later phases add real temporary SQLite/filesystem integration tests, installed C
and C++ consumer tests, migration fixtures, fuzz targets, and relocation E2E
coverage. Tests must not require network access, user locale, or wall-clock timing.

