<div align="center">

# Cairn Client

**Turn single-player adventures into shared co-op experiences. One player hosts, friends join directly through Steam, and everyone plays in the same world.**

<br>

[Download Latest Release](https://github.com/Cairn-client/launcher/releases)

</div>

## What is Cairn?

Cairn Client standardizes cooperative modding across different titles. Rather than rebuilding network synchronization, runtime hooks, and launch logic separately for every game, Cairn decouples the platform from the game logic:

* **Centralized Launcher**: Handles session discovery, Steam peer-to-peer networking, mod checksum verification, and prerequisite health checks.
* **Modular Game Profiles**: Each supported game is registered via a lightweight manifest describing executable entry points, required runtimes, payloads, and native hooks.
* **Seamless Steam P2P**: Join friends directly through the Steam overlay without complex port forwarding or third-party VPN tunnels.

## Ecosystem Repositories

| Repository | Description |
| :--- | :--- |
| **[`launcher`](https://github.com/Cairn-client/launcher)** | The core desktop client built with .NET 8 and Blazor / WebView2. |
| **[`games`](https://github.com/Cairn-client/games)** | Central registry containing manifests, requirements, and checksums for all supported games. |

## Quick Start

1. **Grab the Launcher**: Download the latest installer from the [`launcher/releases`](https://github.com/Cairn-client/launcher/releases) page.
2. **Prerequisites**: Ensure you have **Windows 10/11**, the **.NET 8 Desktop Runtime**, and **WebView2** installed (the launcher checks for missing runtimes on launch).
3. **Download a Mod**: Launch Cairn, select your title, and click **Download mod** to fetch verified game files automatically.
4. **Host or Join**: Launch through Cairn and invite your friends via Steam.

## Disclaimer & Licensing

Cairn Client is an independent open-source project and is **not affiliated with, endorsed by, or associated with any featured game studio or publisher**. 

The client is released under the **GNU General Public License v3.0 (GPL-3.0)**.
Please refer to individual repositories for contributor history, lineage, and upstream credits.
