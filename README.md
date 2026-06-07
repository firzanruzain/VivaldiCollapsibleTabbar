# VivaldiCollapsibleTabbar

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Custom Vivaldi CSS to provide a collapsible vertical tab bar, edge padding adjustments, and improved visuals for left/right tab layouts.

## Features
- Collapsible left and right vertical tabbar support
- Adds safe padding to webview/main content when tabbars are present
- Optional blurred background for unified UI modes

## Releases
- v0.1.1 — Refactor vertical tabbar styles (2026-06-07)
	- Removed extra spacing between tabbar and webview container
	- Combined and organized left/right tabbar settings
	- Fixed border-radius and shadow styling
	- Added improved panel styling and transitions
	- Adjusted unified UI overlays and padding

Download the latest builds from the Releases page: https://github.com/firzanruzain/VivaldiCollapsibleTabbar/releases

## Installation
> Use `main.css` from the release.

1. Visit the Releases page and download `main.css` for the desired version.
2. In Vivaldi go to Settings → Appearance → Custom UI Modifications and point to the folder containing `main.css`.
3. (Optional) Enable CSS experiments at `vivaldi://experiments/` if needed.
4. Restart Vivaldi and toggle tabbar auto-hide to see the effect.

For community tips and advanced modding, see: https://forum.vivaldi.net/topic/10549/modding-vivaldi

## Contributing
- Open an issue or submit a PR with specific tweaks or compatibility fixes. Please include your Vivaldi version and a short description of the DOM/state that needed adjustment.

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for full text.

Copyright (c) 2026 mfr.fs

---
Small, focused CSS tweaks to make vertical tabbars behave nicely in Vivaldi. Report issues or requests in the repo.
