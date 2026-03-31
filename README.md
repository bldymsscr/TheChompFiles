# TheChompFiles
A repository for the glyph decoder for Chompyland's dungeon.

# Glyph Decoder Website

A single-file static website for GitHub Pages.

## Features

- **Latin → Glyph**
  - Type English words or sentences
  - Supported letters automatically convert to glyphs
  - Unsupported letters stay unchanged

- **Glyph → Latin**
  - Type glyphs, Latin letters, or both
  - Glyphs decode into Latin letters
  - Existing Latin letters remain Latin

- **Built-in Glyph Keyboard**
  - Click glyph buttons to insert symbols into the decoder input

## Files

- `index.html` — the entire website in one file

## How to publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/ (root)`
5. Save the settings.
6. Wait a minute or two for GitHub Pages to publish your site.

## Notes

The current glyph alphabet only includes these Latin letters:

a, b, c, d, e, f, g, h, i, l, m, n, o, p, r, s, t, u, v, w, y

Letters not included in your provided mapping, such as `j`, `k`, `q`, `x`, and `z`, stay unchanged.
