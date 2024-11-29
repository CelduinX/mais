# MAIS – Minecraft As It Should (Fabric Server Edition)

Welcome to the **Fabric Server Edition** of MAIS – Minecraft As It Should. This version is tailored for server administrators who want to provide their players with the ultimate Minecraft multiplayer experience. With enhanced exploration, visuals, mechanics, and performance, MAIS ensures a smooth and immersive server environment while staying true to the essence of Minecraft.

---

## 📋 Quick Start Guide

### 1. Download the Server Pack
Grab the Fabric server pack from the provided link.

### 2. Create a `start.bat` File
Create a `start.bat` file in the server directory with the following content:
`java -Xms10G -Xmx10G -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs -Daikars.new.flags=true -jar paper.jar --nogui`

### 3. Adjust RAM Allocation
Modify the RAM values in your Java arguments:
- **`-Xms`**: Minimum RAM (e.g., 4G for 4GB)
- **`-Xmx`**: Maximum RAM (e.g., 8G for 8GB or more).

### 4. Save and Start the Server
Save the `start.bat` file and double-click it to start your server.

---

## 🔧 System Requirements

### Minimum for ~10 Players:
- **4-Core CPU**
- **16 GB RAM**
- **SSD** (Solid State Drive for faster data access)
- **10 Mbit Upload** (to ensure smooth player connections)

---

## 🚀 Key Features for Server Administrators

### 🌍 World Generation
- **150+ New Biomes** for breathtaking exploration.
- **200+ Enhanced Structures**, including revamped dungeons, villages, and strongholds.
- **Reimagined Nether and End**, providing a richer multiplayer dimension experience.

### ⚙️ Quality of Life Enhancements
- Improved mechanics for easier multiplayer interactions.
- Optimized performance for smooth gameplay, even with multiple players.
- Integrated voice chat for seamless communication.

### 🛠️ Performance Optimizations
- Powered by **Sodium**, **Lithium**, and other Fabric performance mods.
- Efficient chunk loading and entity rendering for minimal lag.

---

> Get started with MAIS and bring your multiplayer Minecraft server to life with the perfect blend of innovation and tradition!