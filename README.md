# shortcuts

Shortcuts for macOS, Dex Samsung, Linux Hyprland (yes!) and Windows (iugh).

**Live page: https://italosalgado14.github.io/shortcuts/**

One page that translates my Hyprland habits to Windows 11, macOS and Samsung DeX:

- **Compare**: one row per habit (close a window, go to workspace 3, screenshot, type ñ…) across all four systems, with muscle-memory traps flagged.
- **One tab per system** (Hyprland, Windows, macOS, DeX): how the system thinks, the keys on the keyboard, a setup checklist, all shortcuts, typing Spanish, optional power-ups, traps and sources.

Deep links: `#compare`, `#hyprland`, `#windows`, `#macos`, `#dex`, and sections such as `#macos-setup` or `#dex-shortcuts`.

## Editing

Everything is in `index.html`. The content is the JSON block `<script type="application/json" id="guide-data">`; the page renders from it. Key combos follow one format:

- `"Super + Shift + 1"`: keys pressed together, joined with ` + `
- `"Cmd + Shift + 4, then Space"`: a sequence
- `"gesture: 3-finger swipe up"`: mouse, trackpad or touch
- several entries in a `keys` array are alternatives

In prose, `[[Cmd + W]]` renders as keycaps and backticks render as code.
