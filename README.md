<div align="center">

<img src="https://github.com/simpleappzco/simpleedit/raw/main/SimpleEdit/Assets.xcassets/AppIcon.appiconset/icon_128x128@2x.png" width="128" height="128" alt="SimpleEdit Icon"/>

# SimpleEdit

**A professional text and code editor for macOS — built natively with SwiftUI.**  
No subscriptions. No bloat. Just a fast, clean editor that gets out of your way.

[![Release](https://img.shields.io/github/v/release/simpleappzco/simpleedit?color=black&label=latest)](https://github.com/simpleappzco/simpleedit/releases/latest)
[![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-black)](https://github.com/simpleappzco/simpleedit)
[![License](https://img.shields.io/badge/license-MIT-black)](LICENSE)
[![Made by SimpleAppz](https://img.shields.io/badge/by-SimpleAppz-black)](https://simpleappz.com)

[**Download**](https://github.com/simpleappzco/simpleedit/releases/download/v1.0/SimpleEditV1.0.zip) · [**Website**](https://simpleappz.com) · [**Instagram**](https://www.instagram.com/simpleappz_)

</div>

---

## Features

- **Syntax Highlighting** — 16 languages: Swift, Python, JavaScript, TypeScript, C/C++, Java, Go, Rust, Bash, JSON, XML, HTML, CSS, Markdown, SQL, Plain Text
- **Multi-Tab Editing** — unlimited tabs with full session restore on relaunch
- **Find & Replace** — live match highlighting, match counter, regex support, case-sensitive toggle
- **4 Themes** — Dark, Light, Monokai, Solarized Dark
- **Synchronized Line Numbers** — gutter stays in sync with scroll at all times
- **Duplicate Detection** — highlight all duplicate lines instantly
- **Minimap** — bird's-eye view of your file with click-to-navigate
- **Text Tools** — sort lines, trim trailing spaces, remove duplicates, indent/dedent, uppercase/lowercase
- **Status Bar** — live line/col, word count, char count, encoding, language picker
- **Drag & Drop** — drop any file onto the window to open it
- **Open Recent** — native macOS Open Recent menu support
- **Tab Management** — rename tabs, reorder (right-click context menu), reopen closed tabs
- **Unsaved Indicator** — orange dot on tabs with unsaved changes, save dialog on close
- **Settings** — font size, theme, word wrap, line numbers, minimap — all persisted

---

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon or Intel Mac

---

## Installation

### Download (Recommended)

1. Download [**SimpleEditV1.0.zip**](https://github.com/simpleappzco/simpleedit/releases/download/v1.0/SimpleEditV1.0.zip)
2. Unzip and drag **SimpleEdit.app** to your `/Applications` folder
3. **First launch only:** right-click the app → **Open** → **Open**
   > This is required once because the app is currently unnotarized. We're working on getting an Apple Developer account for future releases.

---

## Build from Source

### Prerequisites
- Xcode 15 or later
- macOS 14 SDK

### Steps

```bash
# Clone the repo
git clone https://github.com/simpleappzco/simpleedit.git
cd simpleedit

# Open in Xcode
open SimpleEdit.xcodeproj
```

Then press **⌘R** to build and run.

---

## Project Structure

```
SimpleEdit/
├── SimpleEditApp.swift       # App entry point, menu commands, AppDelegate
├── ContentView.swift         # Main editor UI, all views and logic
└── Assets.xcassets/
    └── AppIcon.appiconset/   # App icon — all required macOS sizes
```

---

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| New Tab | ⌘T |
| Open File | ⌘O |
| Save | ⌘S |
| Save As | ⌘⇧S |
| Find / Replace | ⌘F |
| Indent | ⌘] |
| Dedent | ⌘[ |
| Undo | ⌘Z |
| Redo | ⌘⇧Z |
| Reopen Closed Tab | ⌘⇧T |

---

## Roadmap

- [ ] Notarized release (Apple Developer Program)
- [ ] Mac App Store listing
- [ ] Auto-update via Sparkle
- [ ] Additional themes
- [ ] More apps from SimpleAppz

---

## Contributing

Bug reports and feature requests are welcome! Open an [issue](https://github.com/simpleappzco/simpleedit/issues) or submit a pull request.

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

Built by [SimpleAppz](https://simpleappz.com) · [Instagram](https://www.instagram.com/simpleappz_) · [GitHub](https://github.com/simpleappzco)

</div>
