# leoterm

A native macOS terminal emulator built with Swift and AppKit.

## Features

- **Native macOS app** — built with Swift and AppKit, lightweight and fast
- **Tabs** — custom tab bar with easy tab management
- **Split panes** — split terminals vertically or horizontally (`⌘D` / `⌘⇧D`)
- **Customizable profiles** — configure colors, fonts, opacity, cursor style, and scrollback
- **Built-in themes** — Default (dark), Solarized Light, and Pro Dark
- **Transparency** — per-profile background opacity support
- **Find in terminal** — built-in search (`⌘F`)
- **Zoom** — adjust font size (`⌘+` / `⌘-`)

## Requirements

- macOS 13 (Ventura) or later
- Xcode 14+ or Swift 5.9+

## Build & Run

```bash
# Build release binary
make build

# Build and launch the app
make run

# Debug build
make debug-app
make run-debug
```

Or use SwiftPM directly:

```bash
swift build -c release
swift build
```
Build·Big PickleOpenCode Zen
## Key Bindings

| Shortcut | Action |
|----------|--------|
| `⌘N` | New window |
| `⌘T` | New tab |
| `⌘W` | Close tab |
| `⌘⇧W` | Close window |
| `⌘D` | Split pane vertically |
| `⌘⇧D` | Split pane horizontally |
| `⌘⌥⇧W` | Close current pane |
| `⌘⌥←` / `⌘⌥→` | Move focus between panes |
| `⌘⇧[` / `⌘⇧]` | Previous / Next tab |
| `⌘F` | Find |
| `⌘+` / `⌘-` | Zoom in / out |
| `⌘0` | Reset font size |

## Credits

- [SwiftTerm](https://github.com/migueldeicaza/SwiftTerm) — terminal emulation library

+ Thought: 238ms
Here's the README content you can copy and paste into your repo:
# leoterm

A native macOS terminal emulator built with Swift and AppKit.

## Features

- **Native macOS app** — built with Swift and AppKit, lightweight and fast
- **Tabs** — custom tab bar with easy tab management
- **Split panes** — split terminals vertically or horizontally (`⌘D` / `⌘⇧D`)
- **Customizable profiles** — configure colors, fonts, opacity, cursor style, and scrollback
- **Built-in themes** — Default (dark), Solarized Light, and Pro Dark
- **Transparency** — per-profile background opacity support
- **Find in terminal** — built-in search (`⌘F`)
- **Zoom** — adjust font size (`⌘+` / `⌘-`)

## Requirements

- macOS 13 (Ventura) or later
- Xcode 14+ or Swift 5.9+

## Build & Run

```bash
# Build release binary
make build

# Build and launch the app
make run

# Debug build
make debug-app
make run-debug
Or use SwiftPM directly:
swift build -c release
swift build
Key Bindings
Shortcut	Action
⌘N	New window
⌘T	New tab
⌘W	Close tab
⌘⇧W	Close window
⌘D	Split pane vertically
⌘⇧D	Split pane horizontally
⌘⌥⇧W	Close current pane
⌘⌥← / ⌘⌥→	Move focus between panes
⌘⇧[ / ⌘⇧]	Previous / Next tab
⌘F	Find
⌘+ / ⌘-	Zoom in / out
⌘0	Reset font size
Credits
SwiftTerm (https://github.com/migueldeicaza/SwiftTerm) — terminal emulation library
