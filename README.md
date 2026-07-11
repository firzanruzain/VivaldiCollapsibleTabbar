# VivaldiCollapsibleTabbar

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Custom Vivaldi CSS to provide a collapsible vertical tab bar, edge padding adjustments, and improved visuals for left/right tab layouts.

## Features
- Collapsible left and right vertical tabbar support
- Adds safe padding to webview/main content when tabbars are present
- Optional blurred background for unified UI modes

## Release Notes
See [RELEASE_NOTES.md](RELEASE_NOTES.md) for the full changelog and release note template.

Latest release: v0.1.3
- Tested with Vivaldi 8.1.4087.48 (Official Build) (64-bit)
- UI polish for tab stacking and selector updates
- Hover-based expand behavior for the tabbar
- Improved 2-level tab stacking and scrollbar handling

Download the latest builds from the [Releases page](https://github.com/firzanruzain/VivaldiCollapsibleTabbar/releases)

## Installation
> Use the full CSS set from the release folder, and keep any CSS files you want to apply together in the same folder.

1. Visit the Releases page and download the CSS files you want to use for the desired version.
2. Put all selected `.css` files in the same folder so Vivaldi can load them together.
3. Enable CSS experiments at [vivaldi://experiments/](vivaldi://experiments/) if needed.
4. In Vivaldi go to Settings → Appearance → Custom UI Modifications and point to that folder.
5. Restart Vivaldi and toggle tabbar auto-hide to see the effect.

For community tips and advanced modding, see: https://forum.vivaldi.net/topic/10549/modding-vivaldi

## Contributing
- Open an issue or submit a PR with specific tweaks or compatibility fixes. Please include your Vivaldi version and a short description of the DOM/state that needed adjustment.

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for full text.

Copyright (c) 2026 mfr.fs

---
Small, focused CSS tweaks to make vertical tabbars behave nicely in Vivaldi. Report issues or requests in the repo.
