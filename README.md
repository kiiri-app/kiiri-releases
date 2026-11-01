<p align="center"><img src="https://kiiri.app/assets/icon.svg" width="96" alt="Kiiri"></p>

# Kiiri releases

Desktop builds of [Kiiri](https://kiiri.app), the little cat that lives on your desktop.
This repo holds only release files and the auto-update feed. The source code is in
[kiiri-app/kiiri](https://github.com/kiiri-app/kiiri) (MIT).

**Download:** [latest release](https://github.com/kiiri-app/kiiri-releases/releases/latest) · or [kiiri.app](https://kiiri.app)

| Platform | File |
| --- | --- |
| macOS (Apple silicon) | `Kiiri-<version>-arm64.dmg` |
| macOS (Intel) | `Kiiri-<version>-x64.dmg` |
| Windows | `Kiiri-Setup-<version>.exe` |

Builds are not code-signed yet. On first launch macOS asks you to allow the app in
**System Settings → Privacy & Security → Open Anyway**; on Windows choose
**More info → Run anyway** in SmartScreen.

The app updates itself from this repo (Windows; macOS once builds are signed).
Bugs and ideas: [issues](https://github.com/kiiri-app/kiiri/issues).
