# Release Notes

This file tracks versioned changes for VivaldiCollapsibleTabbar.

## Entry Format
Use this structure for each new release:

```md
## vX.Y.Z
- Vivaldi version tested: X.Y
- Date: YYYY-MM-DD
- Summary: short release summary
- Installation notes: See the [Installation](README.md#installation) section in the README for the required CSS files and auto-hide setup.
- New changes:
  - change one
  - change two
  - compatibility or selector updates
```

## v0.1.4
- Vivaldi version tested: 8.1.4087.58 (Official Build) (64-bit)
- Date: 2026-07-27
- Summary: Sass refactor for the tabbar styles with automated CSS builds
- Installation notes: See the [Installation](README.md#installation) section in the README for the required CSS files and auto-hide setup.
- New changes:
  - Converted the CSS sources to modular Sass entrypoints and shared partials.
  - Split the main tabbar style into two variants: one using the `show` class and one using hover.
  - The `show` version expands the tabbar when Vivaldi adds the auto-hide show state.
  - The hover version expands the tabbar only while the tabbar area is being hovered.
  - Reduced duplication across the tabbar, tab stacking, and webview styles.
  - Added build and watch scripts to generate the compiled CSS outputs.
  - Added a release prep step so CSS is rebuilt automatically before version bumps.
  - Fixed the missing hover animation delay in the collapsible tabbar output.

## v0.1.3
- Vivaldi version tested: 8.1.4087.48 (Official Build) (64-bit)
- Date: 2026-07-12
- Summary: UI polish for tab stacking and selector updates for the latest Vivaldi release
- New changes:
  - Switched the expand action to hover instead of the auto-hide show class.
  - Improved 2-level tab stacking behavior.
  - Hid and showed the scrollbar based on the hovered tab container.
  - Improved tab width handling.
  - Updated selectors to match the latest Vivaldi changes.

## v0.1.2
- Vivaldi version tested: 8.0
- Date: 2026-06-11
- Summary: Styling and UI polish for tab stacking and webview spacing
- New changes:
  - Added 2-level tab stacking styling support.
  - Adjusted tabbar padding and width handling.
  - Added unified-mode tabbar hover shadow.
  - Added webview margin styling.

## v0.1.1
- Vivaldi version tested: 8.0
- Date: 2026-06-07
- Summary: Refactor vertical tabbar styles
- New changes:
  - Removed extra spacing between the tabbar and webview container.
  - Combined and organized left/right tabbar settings.
  - Fixed border-radius and shadow styling.
  - Added improved panel styling and transitions.
  - Adjusted unified UI overlays and padding.