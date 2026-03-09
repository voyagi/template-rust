# Project Instructions

## Language: Rust

## Build & Test

- Build: `cargo build`
- Test: `cargo test`
- Lint: `cargo clippy`
- Format: `cargo fmt`
- Check: `cargo check` (fast type-check without codegen)

## Conventions

- Use `cargo fmt` before committing
- Address all `cargo clippy` warnings
- Use `thiserror` for library errors, `anyhow` for application errors
- Prefer `&str` over `String` in function parameters
- Use `#[must_use]` on functions returning important values
- Write doc comments for public items
- Use `#[cfg(test)]` module for unit tests
