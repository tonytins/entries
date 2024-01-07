# Entries

Entries is a Notion client developed in Rust using Tauri as a front-end. In a browser, Notion eats up a lot of memory, and the official Electron-based desktop app only makes matters worse. I created Entries so I can free up memory.

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

## License

I license this project under the MPL-2.0 license - see [LICENSE](LICENSE) for details.