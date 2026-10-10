# Homebrew Tap

Homebrew tap for KingPsychopath CLI tools.

## Install `rdrop`

```bash
brew tap KingPsychopath/tap
brew install rdrop
```

Upgrade later with:

```bash
brew update
brew upgrade rdrop
```

## Formulae

| Formula | Description |
| --- | --- |
| `rdrop` | Find, review and organize Raindrop bookmarks from a shell or agent |

## Maintenance

Formula files live in `Formula/`.

For a new `raindrop-cli` release:

1. Update `Formula/rdrop.rb` with the new tag URL.
2. Update the `sha256` for the source archive.
3. Run `brew install --build-from-source KingPsychopath/tap/rdrop` after the tap update is available, then `brew test rdrop`.
4. Commit and push the formula update.
