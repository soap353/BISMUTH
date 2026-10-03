# BISMUTH

BISMUTH is a desktop application for hosting and managing Minecraft and Rust dedicated servers easily and locally. It handles server installation, process management, port forwarding, backups, and server administration.

## Supported Servers

- **Minecraft Java Edition**: Paper, Fabric, Vanilla, Purpur, Spigot (with automatic Java 21/25 detection).
- **Minecraft Bedrock Edition**: Official Bedrock Dedicated Server (BDS).
- **Rust**: Dedicated server via SteamCMD (with Carbon and Oxide/uMod support).

## Features

- **Server Lifecycle**: Start, stop, restart, console stream, command dispatch, and crash recovery.
- **Networking**: UPnP port forwarding via `nat-upnp`, local network IP detection, and manual port configuration.
- **Crossplay**: GeyserMC and Floodgate integration for Bedrock clients joining Java servers.
- **Live World Map**: Squaremap integration for browser-based 2D map rendering and player tracking.
- **Player Stats**: Player session tracking, playtime, in-game statistics, and CSV export.
- **Backups**: Snapshot creation (ZIP) and dimension export.
- **Mod Management**: File browser, log viewer, and mod/plugin installer.

## Download

### Windows
1. Download [`BISMUTH-Portable.zip`](https://github.com/soap353/bismuthp/releases/latest/download/BISMUTH-Portable.zip) or [`BISMUTH.exe`](https://github.com/soap353/bismuthp/releases/latest/download/BISMUTH.exe).
2. Extract the archive.
3. Run `BISMUTH.exe` (requires Node.js LTS).

### Linux
1. Download [`BISMUTH-Linux-Portable.zip`](https://github.com/soap353/bismuthp/releases/latest/download/BISMUTH-Linux-Portable.zip).
2. Extract the archive.
3. Run `./start-bismuth.sh` or launch `BISMUTH-Linux.desktop`.

## License

MIT. See [LICENSE](./LICENSE).

