# BlushCut — Aeiria's pink Concat fork

BlushCut is an independently modified Android build of [Concat](https://github.com/jub0t/Concat).
It is **not** an official release or endorsed by the original Concat developer.

## Design

- Light UI is the default: strawberry-milk pink panels, soft pink inputs, charcoal gutters and high-contrast dark text.
- Rose is the default selection/focus accent; users may choose a different accent or dark mode in Settings.
- Video preview remains neutral black, so the theme does not tint footage.
- Android launcher uses an original pink film-frame icon (`res/drawable/ic_launcher_blush.xml`, with a matching editable `assets/blushcut-icon.svg`).
- Android package ID is `app.aeiria.blushcut`, so it may install alongside official Concat.

## Build

Use the upstream Android build instructions in `README.md` and `.github/workflows/mobile.yml`.
The Android cargo-apk output is `BlushCut.apk`; the workflow names its arm64 artifact `BlushCut-android-arm64`.
No APK is bundled in this branch. Compile and test before installing on a device.

## License and provenance

Based on Concat by Jareer Abdullah and contributors. Code changes remain under
AGPL-3.0-or-later. The Concat name and logo belong to their respective owner;
the BlushCut icon is an original replacement for this fork.
