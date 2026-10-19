# Auto-Collapse Sidebar

Collapses Zen's sidebar to a narrow strip of centred icons and expands it on
hover, like Firefox's "expand sidebar on hover". It works with the **Multiple
toolbars** layout and replaces Zen's own collapsed-sidebar mode with one that
expands when you point at it. Nothing is resized: the sidebar slides out from
behind the page, so web pages don't reflow.

## Install

Install it with [Sine](https://github.com/CosmoCreeper/Sine): open the `Sine
Mods` page in Zen's settings and install the `Auto-Collapse Sidebar` mod by 
repository: `JesterMeijin/zen-auto-collapse-sidebar` (currently not available 
in the Sine Marketplace)

<img width="2010" height="842" alt="image" src="https://github.com/user-attachments/assets/cc1e89cd-0b12-4112-b37a-f0f22007fbb8" />

## Requirements

- Browser layout **Multiple toolbars** (Settings → Look and Feel), sidebar in its
  expanded state, sidebar on the **left**.
- The mod switches itself off in other layouts, compact mode, fullscreen,
  customize mode and while Zen's Library is open, and Zen behaves as usual there.
- On macOS the sidebar's top row (window buttons + sidebar toggle) stays visible
  while collapsed and the toolbar starts right of the toggle.
- Animations need *Animation effects* enabled in the OS (with reduced motion on,
  the sidebar opens instantly).

## What it does

- Collapsed: tab, folder, Space and New Tab icons are centred in the strip, labels
  and the audio icon fade out, Essentials show their first column, the bottom
  buttons collapse into a single `»`, the "now playing" card shrinks to the app
  icon, and the top bar (toggle, back, forward, reload) sits above the strip.
- Hover (or an open sidebar menu, or a tab being dragged): the sidebar opens and
  everything animates back to Zen's own layout.

## Options

Open the mod's options in Sine:

- Width of the collapsed strip, expanded width (by default the sidebar's own
  width, or a fixed value), animation duration, expand delay, collapse delay.
- Fine tuning: shift individual icons left/right by a few pixels if a Zen
  update, a theme or your font size changes their alignment.

## Notes

- Dragging the window by the sidebar is disabled while the mod is active
  (needed so hover isn't lost).
- Other mods that restyle the sidebar may conflict.
- Developed and tested on Zen 1.23.x.

## Source

Pure CSS (`chrome.css`) plus `preferences.json`. MIT licensed.
