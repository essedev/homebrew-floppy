# homebrew-floppy

Homebrew tap for [Floppy](https://github.com/essedev/floppy), a shared disk for big files, right in the Finder.

## Install

```sh
brew install --cask essedev/floppy/floppy
```

(Auto-taps; equivalent to `brew tap essedev/floppy && brew install --cask floppy`.)

## Update

```sh
brew update && brew upgrade --cask floppy
```

## First launch note

The app is not distributed with an Apple Developer ID. If macOS blocks it on first launch,
open **System Settings > Privacy & Security** and click **Open Anyway**.

The cask is written by Floppy's release script (`scripts/release-app.sh`) on every release.
