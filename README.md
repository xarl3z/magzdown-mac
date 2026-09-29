# Magzdown for Mac

Read Markdown files on your Mac with the same magazine layout as [magzdown.com](https://www.magzdown.com).

- **Quick Look.** Select a `.md` file in Finder and press Space.
- **Viewer app.** Double-click a `.md` file to open it in a window that reloads when you save the file in your editor.

Mermaid diagrams, KaTeX math, syntax-highlighted code, footnotes and images next to the file all render. Everything runs on your Mac. Your files are never uploaded.

## Install

1. Download [Magzdown.dmg](https://github.com/xarl3z/magzdown-mac/releases/latest/download/Magzdown.dmg).
2. Open it and drag Magzdown to Applications.
3. Open Magzdown once. That registers the Quick Look preview.

Requires macOS 14 or later.

## Make it the default for .md files

Select any `.md` file in Finder, choose File > Get Info, set "Open with" to Magzdown, then click Change All.

## Styles and Pro

Open Magzdown > Settings (⌘,) to pick a style, light and dark themes, and fonts. Quick Look uses the same choices. Color mode follows your system appearance.

Seven styles, two light themes, two dark themes and three fonts are free. A [Magzdown Pro](https://www.magzdown.com/pricing) license unlocks the rest. Paste your license key under Settings > Magzdown Pro.

## Troubleshooting

**Space still shows plain text.** Open Magzdown once, then run `qlmanage -r` in Terminal. If another Markdown Quick Look app is installed, it may be taking priority. Remove it or turn it off in System Settings > General > Login Items & Extensions > Quick Look.

**Found a bug?** [Open an issue](https://github.com/xarl3z/magzdown-mac/issues).

This repository holds releases only. The app's source code is not public.
