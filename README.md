# Superhelten

Small Windows utilities that do one job and stay out of the way.
Each one is a single download, with no account to create.

## Projects

| Project | What it does | Built with | Get it |
| --- | --- | --- | --- |
| **[ChronoDesk](https://github.com/superhelten/chronodesk)** | Transparent always-on-top desktop clock with a stopwatch, a timer and a board showing which stock exchanges are open. | Rust, egui | [Download](https://github.com/superhelten/chronodesk/releases/latest) · [Website](https://superhelten.github.io/chronodesk/) |
| **[TickC](https://github.com/superhelten/TickC)** | Crypto price ticker for the tray, with a chart panel, price alerts and a desktop-wallpaper mode. | C, Win32 | [Download](https://github.com/superhelten/TickC/releases/latest) |
| **[ElytraGuard](https://github.com/superhelten/elytraguard)** | Stops the Elytra anti-cheat service once WARDOGS has closed, so it only runs while you play. | PowerShell | [Download](https://github.com/superhelten/elytraguard/releases/latest) · [Website](https://superhelten.github.io/elytraguard/) |
| **[Tray Monitor](https://github.com/superhelten/tray-monitor-releases)** | System, service and security monitor in the notification area. Closed source; installers only. | Electron, Rust | [Download](https://github.com/superhelten/tray-monitor-releases/releases/latest) |

All of them run on Windows 10 and 11.

## Good to know

- The installers are not code-signed yet, so SmartScreen may warn on first run. ChronoDesk and ElytraGuard publish a `SHA256SUMS.txt` with each release so you can check the file first.
- Found a bug or missing something? Open an issue in the project's repository.
