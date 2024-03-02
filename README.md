# star

simple tar archive compression/decompression tool

## Install

```rust
    cargo install star
```

## Example

```rust
star c foo.xz Cargo.toml to foo/

star c foo.xz from ./**/*.dll to lib/ from ./**/*.exe to bin/

star c foo.xz Cargo.toml to foo/Bar.toml

star x foo.xz

star x foo.xz bar/
```

## more

star --help


License: GPL-3.0-only
