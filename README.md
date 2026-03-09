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
| `ANTHROPIC_API_KEY` | For CI fixer | pr-check-fixer workflow |
| `DISCORD_WEBHOOK_URL` | For notifications | pr-check-fixer workflow |
| `CODEBERG_TOKEN` | For mirroring | mirror workflow |

Without these secrets, the corresponding workflows will fail silently.
