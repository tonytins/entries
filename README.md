# 🗃️ Entries

Entries is a simple, open-source Notion client built on the Tauri framework.

## Quick Start

### Prerequisites

Before you begin, ensure you have the latest versions of the following installed:

- [VS Code](https://code.visualstudio.com/) (or [VSCodium](https://vscodium.com/))
- [Tauri](https://tauri.app/)
- [Rust](https://www.rust-lang.org/tools/install)
- [Deno](https://deno.com/)

### Platform Support

| Platform | 

| Target  | Windows | macOS  | Linux |
| ------- | ------- | ------ | ----- |
| x86_64  | ✅      | ⚠️[^1] | ✅    |
| aarch64 | ❌      | ✅     | ⚠️    |

- ✅ Tier 1
- ⚠️ Tier 2
- ❌ Unsupported

[^1]: [Rust 1.89](https://blog.rust-lang.org/2025/08/07/Rust-1.89.0/) downgrades AMD64 support after Apple and GitHub CI did the same.


## Project Notes

### Background

Entries was created as an alternative to Notion's official Electron-based desktop client after experiencing performance issues from its high memory consumption. At first I tried using PWAs (Progressive Web Apps) through Safari and while it was an improvement, I realized there was no native support for Linux. Not wanting to see myself becoming villain, I searched for an alternative to Electron and that's how I discovered Tauri. While Notion is still a RAM hog (often idling at 800 MBs), Entries' total overhead is only 98 MBs on macOS and just as fast.

## License

Entries is licensed under the GPL-3.0 license. For more information, please refer to the [LICENSE](LICENSE) file in the project repository.

## Disclaimer

_This project is not endorsed by or affiliated with Notion._
