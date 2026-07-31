<div align="center">

<img src="src/main/resources/assets/meteor-client/icon.png" alt="Shard Client Logo" width="96" height="96">

# Shard Client

**A high-performance Minecraft Fabric Utility Mod engineered for anarchy servers, software testing, and developer research.**

[![Fabric API](https://img.shields.io/badge/Modloader-Fabric-blue?style=for-the-badge&logo=fabric)](https://fabricmc.net/)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.17.x%20--%2026.x-brightgreen?style=for-the-badge&logo=minecraft)](https://minecraft.net/)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/b5b9qNWHWz)
[![License](https://img.shields.io/badge/License-GNU-orange?style=for-the-badge)](LICENSE)

</div>

---

> [!CAUTION]
> Shard Client is an open-source project developed for **educational purposes, protocol testing, and software research within controlled environments**. Users are responsible for complying with the rules and guidelines of > any server they connect to.

---

## ✨ Key Features

### ⚔️ Combat
* **CrystalAura, BedAura & AnchorAura** — Automated crystal placement, bed detonator, and anchor charging.
* **AutoTotem & Offhand** — Smart offhand management and low-health emergency totem swapping.
* **Surround & SelfTrap** — Automated obsidian placement for blast protection and self-defense.
* **AutoCity & HoleFill** — Breaker logic for enemy feet-blocks and 1x1 hole denial.
* **KillAura & TriggerBot** — Entity attack automation with weapon rotation and cooldowns.

### 🏃 Movement
* **ElytraFly & PacketFly** — High-speed highway travel modes and phase flight capabilities.
* **Speed, Velocity & Step** — Customizable movement tweaks, instant stepping, and knockback reduction.
* **Jesus, SafeWalk & EntityFly** — Fluid interaction with liquids, safe block-edge traversal, and mount controls.

### 👁️ Render
* **Storage & Player ESP** — Highlights chests, shulker boxes, ender chests, and players through walls.
* **Tracers & Nametags** — Vector lines pointing to nearby entities with detailed HUD info overlays.
* **NewChunks & Waypoints** — Detects freshly generated chunks for base hunting and custom 3D coordinate pins.
* **Fullbright & Freecam** — Maximum night vision lighting overrides and detached camera scouting.

### ⛏️ World & Utility
* **PacketMine & SpeedMine** — Background block breaking packets and mining speed tweaks.
* **Baritone Integration** — Fully compatible with Baritone pathfinding for automated navigation.
* **AutoLog & AutoRespawn** — Automatic safety disconnects and death screen skips.
* **Discord RPC** — Customizable status presence showing current server IP, coordinates, and health.

---

## ⚙️ Installation

1. Download and install **[Fabric Loader](https://fabricmc.net/use/installer/)** for your target Minecraft version.
2. Download the matching **[Fabric API](https://modrinth.com/mod/fabric-api)** mod `.jar`.
3. Download the latest release of **Shard Client** from the [Releases Page](https://github.com/Syntax-Studios-11010/Shard-Client/releases).
4. Place both `.jar` files into your `.minecraft/mods` directory.
5. Launch Minecraft using the Fabric profile.

---

## 🛠️ Building from Source

To build Shard Client yourself from source code:

```bash
# Clone the repository
git clone [https://github.com/Syntax-Studios-11010/Shard-Client.git](https://github.com/Syntax-Studios-11010/Shard-Client.git)

# Navigate into the directory
cd Shard-Client

# Build using the Gradle wrapper
./gradlew build

The compiled .jar file will be generated in the build/libs/ directory.

# 🤝 Contributing & Support
Contributions, issue reports, and pull requests are welcome!
Found a bug? Open an issue on our GitHub Issues tab.
Need help or want to join the community? Join our Discord Server.

# 📜 License
This project is licensed under the GNU General Public License v3.0.
