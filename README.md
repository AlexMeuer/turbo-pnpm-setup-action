# Turbo PNPM Setup Action

What does this action do?

- Uses a local cache for turborepo
- Sets up Node.js
- Installs Pnpm
- Installs node dependencies
  - Uses a cache for dependencies

## Usage

```yaml
- uses: AlexMeuer/turbo-pnpm-setup-action@v1
  with: # All inputs are optional
    turbo-cache-dir: .turbo
    node-version-file: .nvmrc
    install-deps: true
    pnpm-version: 8
```

