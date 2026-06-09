# homebrew-tap

[i-Willink](https://i-willink.com) の OSS 向け Homebrew tap。

## Agent Deck（macOS / Apple Silicon）

```sh
brew install --cask willink-oss/tap/agentdeck
```

未署名配布のため、初回起動は Gatekeeper の回避が必要です（cask の `caveats` 参照、
または `xattr -dr com.apple.quarantine "/Applications/Agent Deck.app"`）。

- リポジトリ: https://github.com/willink-oss/agentdeck
- 製品ページ: https://i-willink.com/products/agentdeck
