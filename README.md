Rust implementation of alvm.


Build weels

```
$ docker run --rm -v $(pwd):/io konstin2/maturin build --release

```

Note that for now, you must use the `use_alvm_rs` branch of `alvm`.

The rust code replaces `run_program` and `ALVMObject`.

In order to run the unit tests, one has to pass `--no-default-features` to `cargo test`:

```
cargo test --no-default-features
```
