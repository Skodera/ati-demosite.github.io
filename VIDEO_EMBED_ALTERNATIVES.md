# Video embed: zero YouTube recommendations

If you need **no** pause/end-screen recommendations at all, a standard YouTube iframe cannot guarantee that.

**Option A — Self-hosted HTML5 video**

- Export the clip as MP4 (and optionally WebM).
- Add the file under this site (e.g. `videos/hero.mp4`).
- Replace the iframe in `index.qmd` with `<video controls playsinline poster="...">` pointing at that file. You get full control over UI; no YouTube overlays.

**Option B — Other hosts**

- Some paid or institutional hosts offer embeds with stricter end screens; compare terms and cost.

See also the HTML comment above the iframe in `index.qmd` for `rel=0` behavior on YouTube.
