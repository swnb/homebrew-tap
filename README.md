# swnb/homebrew-tap

Official Homebrew Tap for [LynxBar](https://github.com/swnb/lynxbar).

## Install LynxBar

```sh
brew install --cask swnb/tap/lynxbar
```

## Upgrade

```sh
brew upgrade --cask swnb/tap/lynxbar
```

## Uninstall

```sh
brew uninstall --cask --zap swnb/tap/lynxbar
```

## Notes

- Installs the Universal Binary (`arm64` + `x86_64`) for macOS 13.0 (Ventura) or later.
- Verifies the exact `SHA-256` checksum from GitHub Releases and clears the macOS Gatekeeper quarantine attribute automatically during `postflight`.
