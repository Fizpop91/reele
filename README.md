# Reele - Location & Post Audio Workflow Toolkit

Reele is a native macOS SwiftUI app for audio/video conversion workflows and PolyWAV metadata/report operations, using `FFmpeg`.

The FFmpeg binary needs to be installed to use this app. You can either download it and pass it to the app or install it via Homebrew.
If you download the binary, because of macOS's Gatekeeper security feature, you need to run it once, then go to `System Settings -> 
Privacy & Security` and click "Open Anyway". This process also applies to the app itself.

## Core Principles

- Native macOS app built around `operation` cards and queue-driven processing.
- `FFmpeg` is not bundled by default; users select a binary, and Reele manages it.
- Command transparency: each workflow shows a command preview and supports one-click copy 
  so the user can run it directly in Terminal if they choose.
- Template workflow: built-in templates + custom templates where supported.
- Drag and drop of operation cards in `Home` and `Other` windows.

---

See the [wiki](https://github.com/Fizpop91/reele/wiki) for a full feature overview.
