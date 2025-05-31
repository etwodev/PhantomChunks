# PhantomChunks

**PhantomChunks** is a Minecraft plugin for Paper servers that enables per-player virtual environments within a single shared world. Players can occupy the same coordinates but perceive entirely different structures, landscapes, or objects enabling isolated builds, private housing, or mini-game arenas without needing separate worlds or servers.

This plugin also includes a virtual height extension system, allowing players to seamlessly move beyond Minecraft's vanilla Y-height limit by teleporting them between chunk slices and modifying the chunk data they receive.

## Features

- [ ] **Per-player chunk rendering:** Each player can see different versions of the same area.
- [ ] **Virtual domains:** Isolated environments for housing, private builds, or game instances.
- [ ] **Extended vertical space:** Simulate infinite height by layering world slices.

## Installation

1. Download the latest [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) and place it in your server's `plugins/` directory.
2. Download the `PhantomChunks` plugin (build from source or release).
3. Place `PhantomChunks.jar` into the `plugins/` folder.
4. Start your Paper server (1.20.4+ recommended).

## Usage (Planned)

> Basic usage and commands are under development. Initial prototype includes:
- API for assigning players to domains.
- Experimental chunk rendering overrides.
- Prototype teleportation for vertical extension.
- `/domain set <player> <domain>` command
- In-game domain creation tools
- Persistent domain data

## Developer Guide

This plugin is written in **Kotlin** using the **PaperMC API** and **ProtocolLib**.

### Requirements

- Java 17+
- Gradle (via IntelliJ or CLI)
- IntelliJ IDEA (recommended)

### Build

```bash
./gradlew build
