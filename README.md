# my-spicetify-snippets

Collection of Spicetify CSS snippets. Tested with the `Blacksuan19` theme.

## Contents

- `index.css` — combined stylesheet with all tweaks.
- `snippets/` — per-tweak files (one file per tweak).
- `screenshot.png` — example preview.

## Usage

1. Copy `index.css` into your theme's custom CSS (or copy desired file(s) from `snippets/` into your custom CSS).
2. Apply changes:

```/dev/null/usage.sh#L1-2
spicetify apply
```

To disable a tweak, remove or comment its block from the custom CSS and re-run the apply command.

## Snippets

- `01-better-lyrics.css` — emphasize the active lyric line.
- `02-hide-sidebar-scrollbar.css` — hide left sidebar scrollbar handles/tracks.
- `03-modern-scrollbar.css` — thin, rounded scrollbar that widens on hover.
- `04-pretty-lyrics.css` — hide lyrics background; fade non-active lines.
- `05-oneko.css` — animated sprite on the playback progress bar (external GIF).
- `06-smaller-right-cover.css` — shrink right-side cover art and compact layout.
- `07-remove-top-gradient.css` — remove header/playlist background gradients.
- `08-hide-recently-played.css` — hide "Recently played" and home shortcuts sections.
- `09-queue-top-side-panel.css` — move queue to the top of the right-side panel.
- `10-remove-playlist-cover.css` — hide large playlist/album cover in headers.

## Preview

![Preview screenshot](preview.png)

Preview: playlist view with several tweaks applied (smaller right-side cover art, adjusted lyrics styling, removed top gradient, queue side panel, etc.).

## Notes

- Theme: built and tested for `Blacksuan19`. Other themes may require minor selector or spacing adjustments.
- Maintenance: Spotify's DOM and class names can change; update selectors if a snippet stops working.
