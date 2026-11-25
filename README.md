# 12col

Make column and row grid guides for any canvas size, preview them live, and export them as a PNG. Everything runs in the browser.

Live at [12col.xyz](https://12col.xyz).

## Use

- Set the canvas size (default 1920 × 1080), columns, rows, column and row gutters, and margins.
- Pick a line colour and thickness, or turn on a transparent background.
- Optionally tint the columns, rows or cells, and add center, thirds, action-safe and title-safe guides.
- **Export PNG** downloads the image. **Copy PNG** puts it on the clipboard; **Copy SVG** copies editable vector lines (paste into Figma or Illustrator).
- The URL always holds your current settings, so **Copy link** shares or bookmarks a grid.
- **Google Slides guides** lists every line's position in inches, ready to place guides in Slides.

## Develop

It's a single static file. Open `index.html` in a browser; there is no build step.

## Deploy

Served by GitHub Pages from the root of `main`. `CNAME` sets the custom domain to `12col.xyz`.
