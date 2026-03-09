# My Project

> Created from [voyagi/template-rust](https://github.com/voyagi/template-rust)

## Getting Started

```bash
# Build
cargo build

# Test
cargo test

# Lint
cargo clippy

# Format
cargo fmt
```

## Post-Create Setup

After creating a repo from this template, configure the following secrets
in **Settings > Secrets and variables > Actions**:

| Secret | Required | Used by |
|--------|----------|---------|
| `CODEBERG_TOKEN` | For mirroring | mirror workflow |

Without this secret, the mirror workflow will fail silently.
