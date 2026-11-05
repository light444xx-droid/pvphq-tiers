# PvPHQ Tiers

Unofficial Minecraft Fabric mod by Light9x that displays player ranks from PvPHQ.com.

## Source code

Download [pvphq-tiers-0.1.12-source.zip](pvphq-tiers-0.1.12-source.zip) and extract it to read, modify, or build the full project. The archive includes Java source, resources, Gradle scripts, the Gradle wrapper, and verification code.

This repository publishes the complete source archive for version 0.1.12, targeting Minecraft 1.21.11.

## Features

- PvPHQ tiers beside player names.
- Press H to open the closest player's profile.
- Current and peak tiers, rating points, and placement progress.
- Real Minecraft item icons that follow the active resource pack.
- Custom colors for individual tiers.

## Build

Install Java 21, extract the source archive, and run the following from the extracted project directory.

Windows:

```bat
gradlew.bat build
```

Linux or macOS:

```sh
sh gradlew build
```

The compiled mod is written to `build/libs/`. Building requires internet access to download dependencies.

## Credits and license

PvPHQ version by Light9x. Based on Tiers 0.8.4 by Flavio6561.

The source is distributed under GPL-3.0. See [LICENSE](LICENSE). PvPHQ branding belongs to its respective owner. This is an unofficial project.
