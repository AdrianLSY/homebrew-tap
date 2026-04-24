# AdrianLSY's Homebrew Tap

Homebrew tap for [AdrianLSY/AeroSpace](https://github.com/AdrianLSY/AeroSpace) —
a fork of [nikitabobko/AeroSpace](https://github.com/nikitabobko/AeroSpace) that
adds hover-to-raise via [AutoRaise](https://github.com/sbmpost/AutoRaise).

## Install

```bash
brew tap AdrianLSY/tap
brew install --cask aerospace-adrianlsy
```

Or one-shot:

```bash
brew install --cask AdrianLSY/tap/aerospace-adrianlsy
```

The `aerospace-adrianlsy` cask `conflicts_with 'aerospace'`, so you can't
install both simultaneously — pick one.

## What's here

- `Casks/aerospace-adrianlsy.rb` — the fork's Homebrew cask. Updated
  automatically by the fork's
  [release workflow](https://github.com/AdrianLSY/AeroSpace/blob/main/.github/workflows/release-adrianlsy.yml)
  on each tag push matching `v*-adrianlsy.*`.

## Updating

New versions are published automatically. When
[AdrianLSY/AeroSpace](https://github.com/AdrianLSY/AeroSpace) tags a release
(e.g. `v0.18.7-adrianlsy.1`), its CI opens a PR against this repo with the
regenerated cask. A maintainer reviews and merges.

See
[dev-docs/fork-maintenance.md](https://github.com/AdrianLSY/AeroSpace/blob/main/dev-docs/fork-maintenance.md)
in the fork repo for the full release protocol.
