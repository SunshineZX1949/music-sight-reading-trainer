[简体中文](README.md) | **English**

# SightRead · Piano Sight-Reading Practice

A single-file, offline-ready piano sight-reading practice web page.

## Usage

Open it directly in your browser:

- `dist/piano-sight-reading.html` (distribution build)
- `index.html` (source file, identical to the distribution build)

On mobile, you can also use the copy already saved to your downloads folder:
`/sdcard/Download/DSH-Go/piano-sight-reading.html`

## Contents

- `index.html` / `dist/piano-sight-reading.html` — self-contained web page with the font embedded
- `assets/music-subset.woff2`, `assets/music-subset.b64` — source files for the embedded font
- `assets/LICENSE-NOTO-MUSIC.txt` — Noto Music font license

## Features

- Switch between treble clef, bass clef, and grand staff
- Freely choose the note range to practice
- Key-signature practice with 0–7 sharps
- Standard black-and-white highlighted piano keys with horizontal scrolling
- On a wrong answer, the wrong note is marked in red on the staff and the correct key is highlighted
- Three interface themes: Current, White, and Black
- Automatically detects your browser language: Chinese browsers get Chinese, all others get English
- Manually switch between “Auto / 中文 / English” in settings; your choice is saved locally
