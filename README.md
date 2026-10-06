# Camptx Homebrew tap

Homebrew distribution for [Murmur](https://github.com/camptx/murmur), offline English dictation for Apple Silicon Macs.

The first signed release has not been published yet. Murmur's tag-triggered release workflow creates and updates the cask after it verifies the published download.

Once the first release is available, install with:

```bash
brew install --cask camptx/tap/camptx-murmur
```

To update or uninstall:

```bash
brew upgrade --cask camptx/tap/camptx-murmur
brew uninstall --cask camptx/tap/camptx-murmur
```

Open Murmur, grant Microphone and Accessibility access, and download the English speech model in Settings.

Release automation owns `Casks/camptx-murmur.rb`. Its download URL and checksum refer to the signed, notarized GitHub release. See [release setup](https://github.com/camptx/murmur/blob/main/docs/RELEASING.md) for maintainer instructions.

[MIT license](LICENSE)
