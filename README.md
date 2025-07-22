### Prerequisites
1. Install [rust](https://www.rust-lang.org/tools/install)
2. Install [windows toolchain](https://rust-lang.github.io/rustup/installation/windows.html)

### Usage
1. Run `cargo run --bin builder -- <file>`
2. Run `cargo build --release --target=x86_64-pc-windows-msvc --lib`

### Disclaimer
Build the runtime for the same architecture as your target process.

### Contributing
1. Fork it
2. Create your branch (`git checkout -b my-change`)
3. Commit your changes (`git commit -m "changed something"`)
4. Push to the branch (`git push origin my-change`)
5. Create new pull request
