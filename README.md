# Dress Up Classic

ZC's Dress Up is my original version of my first (and only) flash game I ever got around to making. Dress Up Classic is an attempt to bring that to the desktop using Tauri and Ruffle while also getting myself familar with the vanilla architecture.

## Background

Flash game, aside, this is not the first time I've brought this simple game to a somewhat wider audience in order to get familiar with a web framework. The first time (and where much of the additional assets originate from, such as the CSS code) was as a packaged Chrome App. It stayed on the Web Store until Flash was discontinued.


I didn't think I'd be digging out this old code again for yet another experiment. So far, it works well in development builds. Production, not so much. Regardless, Tauri solves a lot of the shortcomings of Electron while adopting the good aspects we've come to expect from applications built with it, such as auto-updating.

## Requirements

### Supported Platforms

| Platform | Versions                           |
| -------- | ---------------------------------- |
| Windows  | 7 or later                         |
| macOS    | 10.15 or later                     |
| Linux    | webkit2gtk 4.1 (e.g. Ubuntu 20.04) |

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) 2021 edition
  - [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [VS Code](https://code.visualstudio.com/)
  - [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)