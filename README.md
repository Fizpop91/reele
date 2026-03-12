# Reele - Location & Post Audio Workflow Toolkit

**Reele** is a native macOS app for audio/video conversion workflows and PolyWAV metadata/report operations, mostly built around `FFmpeg`.

<img width="100%" alt="01_Reele_Home" src="https://github.com/user-attachments/assets/c5ed1cae-4874-4da3-be45-c53110dbaddf" />
<img width="100%" alt="02_Reele_Other" src="https://github.com/user-attachments/assets/acf403f6-dd43-40ae-aea0-52600a0b42a6" />

The FFmpeg binary needs to be installed to use this app. You can either [download it](https://www.osxexperts.net/) and pass it to the app or install it via Homebrew.
If you download the binary, because of macOS's Gatekeeper security feature, you need to run it once, then go to `System Settings -> 
Privacy & Security` and click "Open Anyway". This process also applies to the app itself _(I built this for myself and don't want to pay the €100/year for the Apple Developer Program)_.

## Core Principles

- Native macOS app built around `ffmpeg` using `operation` cards and queue-driven processing.
- `FFmpeg` is not bundled by default; users select a binary, and Reele manages it.
- FFmpeg command transparency: each workflow shows a command preview and supports one-click copy so the user can run it directly in Terminal if they choose.
- Template workflow: choose from a built-in template or create your own custom templates where supported.
- Drag and drop to reorder operation cards in `Home` and `Other` windows.

---

See the [wiki](https://github.com/Fizpop91/reele/wiki) for a full feature overview.
