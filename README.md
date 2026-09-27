# lobabobloblaw/homebrew-tap

Homebrew casks for [Tokenamp](https://github.com/lobabobloblaw/tokenamp), your Claude plan usage
as a Winamp 2.x player for macOS.

```sh
brew install --cask lobabobloblaw/tap/tokenamp
```

Tokenamp is not notarized by Apple yet, so macOS blocks the first launch after each install or
upgrade; `brew info tokenamp` shows how to allow it.

The cask is generated from the Tokenamp repository by `packaging/homebrew/update_cask.sh`, so
change it there rather than here.
