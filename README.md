# memex-updates

Public static metadata for Memex Sparkle update feeds.

This repository is intentionally small. It is for appcast files, release
metadata, and release directory placeholders only.

Do not commit:

- Memex source code
- Sparkle private keys
- GitHub tokens, Apple credentials, API keys, or passwords
- DMG, app, zip, xcarchive, xcresult, build output, or log artifacts

## Channels

- `alpha/`: alpha channel appcast metadata. There is no published alpha release
  in this initial skeleton.
- `stable/`: reserved for a future stable channel.

The example appcast in `alpha/appcast.xml.example` documents the expected feed
shape only. It is not a live release feed and does not contain any usable
release item.
