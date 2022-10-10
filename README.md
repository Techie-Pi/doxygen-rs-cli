# doxygen-rs-cli

A CLI to interact with [doxygen-rs](https://github.com/Techie-Pi/doxygen-rs).

## Usage
```shell
doxygen-rs-cli bindings.rs new-bindings.rs
```

If you want to overwrite the original file, use the following command:
```shell
doxygen-rs-cli bindings.rs bindings.rs --remove-backup true
```

The ``remove-backup`` parameter ensures that the backup created by the CLI is removed