# Ripple

A small browser tool that slices a glyph into strips and pushes each strip along a sine wave radiating from a point. Export the result as SVG or PNG.

**Live:** https://mnohosmyslov.github.io/ripple-symbol-lab/

## Features

- Type a character or word, pick from eight built-in typefaces, or upload your own font (.ttf, .otf, .woff)
- Or upload any SVG and recolour it
- Slice into columns, rows or concentric rings
- Control wavelength, displacement, phase, falloff and the wave origin (click the preview to move it)
- Per-strip lens, cross offset, stretch and ring twist
- Optional glow and chromatic aberration
- Animate the phase
- Export SVG, PNG 1024 or PNG 2048, with an optional transparent background
- Share a setup as JSON

## Run locally

It is a single self-contained `index.html`. Open it in a browser.

The only external dependencies are [opentype.js](https://github.com/opentypejs/opentype.js) from cdnjs and the UI fonts from Google Fonts.

## Credits

Built-in typefaces (Inter, Manrope, DM Sans, Archivo, Bricolage Grotesque, Syne, Unbounded, Instrument Serif) are licensed under the SIL Open Font License.
