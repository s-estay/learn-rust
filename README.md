## hello word
- Create new file: `touch main.rs`
```rust
fn main() {
    println!("hello world");
}
```
- Compile: `rustc main.rs`
- Run: `./main`
## hello cargo
- `cargo new hello-cargo`
- Build: `cargo build`
- Run: `./target/debug/hello-cargo`
- Build and run: `cargo run`
- Check if code compiles without generating an executable: `cargo check`
- Build for release: `cargo build --release`
## crates
- [crates.io](https://crates.io/)
- Add crate in `Cargo.toml`
- `cargo build`
- `cargo update`