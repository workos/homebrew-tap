# WorkOS Homebrew Formulae

Homebrew formulae for [WorkOS](https://workos.com) tools.

## WorkOS CLI

Our CLI wizard that operates on the WorkOS platform and can automatically integrates WorkOS AuthKit into your app.

### Installing

```bash
brew install workos/tap/workos
```

### Updating

```bash
brew upgrade workos
```

## WorkOS Emulator

Local WorkOS API emulator for tests and development.

```bash
brew install workos/tap/workos-emulate
```

## Updating

```bash
brew upgrade workos-emulate
```

## Contributing

The formulae in `Formula/` are generated and pushed by release automation in
[workos/cli](https://github.com/workos/cli) and
[workos/emulate](https://github.com/workos/emulate). Edits made here are
overwritten by the next release; change the generators instead.
