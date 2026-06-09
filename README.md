# leoterm

A native macOS terminal emulator built with Swift and AppKit.

## Features

- **Native macOS app** — lightweight, fast, built with Swift and AppKit
- **Tabs** — custom tab bar with drag reordering, activity indicators, and auto-hide
- **Split panes** — vertical and horizontal splits, nested split support (`⌘D` / `⌘⇧D`)
- **Customizable profiles** — configure colors, fonts, opacity, cursor style, and scrollback lines
- **Built-in themes** — Default (dark), Solarized Light, and Pro Dark
- **Profile import/export** — share terminal profiles via JSON files
- **Transparency** — per-profile background opacity
- **Find in terminal** — built-in search (`⌘F`)
- **Font zoom** — adjust font size on the fly (`⌘+` / `⌘-` / `⌘0`)
- **System monitor** — live CPU, memory, disk, network, and battery gauges with process table
- **AI assistant** — built-in integration with Ollama (local) and OpenAI-compatible APIs for system analysis and Q&A
- **Terminal inspector** — debug panel showing cursor position, scrollback, and buffer stats
- **Visual bell** — flash overlay on BEL characters
- **Notification on bell** — macOS notification when terminal bell fires while backgrounded
- **Safe paste** — bracketed paste mode (`⌘⇧V`)
- **Copy on select** — auto-copy text to clipboard on mouse selection
- **Key bindings** — fully customizable keyboard shortcuts with in-app editor
- **Option as Meta** — Option key sends ESC prefix for Emacs-style keybindings
- **Session persistence** — window state restoration across app restarts
- **Confirm before close** — warns about running processes when closing tabs
- **File drag-and-drop** — drag files into terminal to insert quoted paths

## Requirements

- macOS 13 (Ventura) or later
- Xcode 14+ or Swift 5.9+

## Build & Run

```bash
# Build release binary
make build

# Build release .app and launch
make run

# Debug build
make debug
make debug-app
make run-debug

# Clean artifacts
make clean
```

Or use SwiftPM directly:

```bash
swift build -c release
swift build
swift run leoterm-tests   # Run terminal emulation test suite
```

## Key Bindings

| Shortcut | Action |
|----------|--------|
| `⌘N` | New window |
| `⌘T` | New tab |
| `⌘⇧T` | Duplicate tab |
| `⌘W` | Close tab |
| `⌘⌥⇧W` | Close pane |
| `⌘D` | Split pane vertically |
| `⌘⇧D` | Split pane horizontally |
| `⌘⌥←` / `⌘⌥→` | Move focus between panes |
| `⌘⇧Tab` / `⌘Tab` | Next / Previous tab |
| `⌘F` | Find in terminal |
| `⌘+` / `⌘-` | Zoom in / out |
| `⌘0` | Reset font size |
| `⌘⇧A` | Show Activity Monitor |
| `⌘⇧I` | Toggle terminal inspector |

All key bindings are customizable via Preferences → Keys.

## Credits

- [SwiftTerm](https://github.com/migueldeicaza/SwiftTerm) — terminal emulation library
