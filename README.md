# Sandbox Dump

## Creating a Template 
To get started, make sure your `.tar.gz` file's contents are not in a sub folder. Here is a convention to follow:

    # rust.tar.gz | rust-min

    ├── src                     # Source Directory
    └── Cargo.toml              # Rust Project Manifest File

Then use a tool like `tar` to compress it into an archive:
```
$ tar -czvf rust.tar.gz Cargo.toml -C src/ .
```
