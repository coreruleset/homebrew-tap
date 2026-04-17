# homebrew-tap

Official Homebrew tap for OWASP CRS tools.

This tap provides Homebrew cask formulae for [crs-toolchain](https://github.com/coreruleset/crs-toolchain) and other OWASP CRS utilities. Cask formulae are automatically updated via [GoReleaser](https://goreleaser.com/) on each release of `crs-toolchain` or other tools in the OWASP CRS organisation.

## Installation

Add this tap to Homebrew:

```sh
brew tap coreruleset/tap
```

Then install a tool, for example `crs-toolchain`:

```sh
brew install crs-toolchain
```

## Upgrade

```sh
brew upgrade crs-toolchain
```

## Uninstall

```sh
brew uninstall crs-toolchain
```

To also remove the tap:

```sh
brew untap coreruleset/tap
```

## Links

- [crs-toolchain repository](https://github.com/coreruleset/crs-toolchain)
- [OWASP CRS project site](https://coreruleset.org)
