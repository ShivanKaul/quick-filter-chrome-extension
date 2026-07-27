# Quick Filter for Gmail

One-click access to Gmail's built-in "Filter messages like these" feature, via
a toolbar button, a keyboard shortcut, or an item in Gmail's own right-click
menu.

This repository is the public home for the extension's Chrome Web Store
materials and issue tracker.


## Privacy

The extension never reads, stores, or transmits your email contents. It has no tracking, and no external servers. See the full
[Privacy Policy](https://shivankaul.com/quick-filter-chrome-extension/privacy/).

## Support

Found a bug or have a feature request? Please
[open an issue](https://github.com/ShivanKaul/quick-filter-chrome-extension/issues).

## Chrome Web Store listing

Copy for the store listing. The 128x128 store icon is
`assets/store-icon-128.png` (regenerate with `npm run store-icon`).

**Single purpose**

> Provides one-click access to Gmail's native message-filtering feature.

**Description**

**Quick Filter for Gmail** gives you one-click access to Gmail's built-in
"Filter messages like these" feature, so you can create filters for unwanted
or repetitive emails without digging through menus.

Select a single conversation, then trigger the filter flow three ways:
- The toolbar button
- A keyboard shortcut (Alt+Shift+F on Windows/Linux, Option+Shift+F on macOS)
- An item added directly to Gmail's own right-click menu

The extension opens the same filter dialog Gmail already provides. On the
filter screen, "Also apply filter to matching conversations" is pre-checked so
you can clean up existing mail in the same step.

**Privacy first**
- Never reads, stores, or transmits your email contents
- No analytics, no tracking, no external servers
- Runs only on mail.google.com
- No account or sign-in required

**Permission justification** (`host_permissions` for `mail.google.com`)

Required to add the filter action to Gmail's UI and activate Gmail's native
"Filter messages like these" flow. The extension runs only on Gmail and does
not access any other sites.

**Category:** Productivity > Tools

## Store assets

Chrome Web Store listing assets live in [`store/`](store/):

- `store/screenshot-in-action.jpg` — 1280x800 listing screenshot
- `store/store-icon-128.png` — 128x128 store icon
