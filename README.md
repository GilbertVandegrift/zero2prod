curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
//^install rust

cargo install cargo-watch

rustup component add llvm-tools-preview

cargo install cargo-llvm-cov

rustup component add clippy

rustup component add rustfmt

cargo install cargo-audit
//^some set up commands in linux

rust-analyzer // extension on vs code

cargo watch -x check -x test -x run
cargo clippy // for idiomatic code

cargo fmt // formats, can add rustfmt.toml to specify how
