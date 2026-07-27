# WorkOS Homebrew Formulae

Homebrew formulae for [WorkOS](https://workos.com) tools.

## WorkOS CLI

```bash
brew install workos/tap/workos
```

## WorkOS Emulator

Local WorkOS API emulator for tests and development. Ships as a standalone
binary, so it runs without a Node toolchain.

```bash
brew install workos/tap/workos-emulate
```

## Updating

```bash
brew upgrade workos
brew upgrade workos-emulate
```

## Contributing

The formulae in `Formula/` are generated and pushed by release automation in
[workos/cli](https://github.com/workos/cli) and
[workos/emulate](https://github.com/workos/emulate). Edits made here are
overwritten by the next release — change the generators instead.
