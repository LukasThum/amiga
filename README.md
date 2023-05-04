# Amiga with FS-UAE

This project contains configuration files for running Amiga games and software using the FS-UAE emulator on macOS. The configurations are stored in a Git repository, allowing easy sharing and synchronization among multiple users.

## Directory Structure

The project is organized into the following directory structure:

```bash
.
├── configs
├── floppies
│ ├── <game_disk1>.adf
│ ├── <game_disk2>.adf
│ └── ...
└── kickstarts
├── kick130.rom
└── kick314.rom
```

- `configs`: Contains FS-UAE configuration files for each game or software.
- `floppies`: Stores the game disk files (ADF, ADZ, DMS, IPF) used by the configurations.
- `kickstarts`: Contains the Kickstart ROM files required for booting the Amiga emulator.

## Prerequisites

- Install FS-UAE on your macOS system by downloading it from the official website: https://fs-uae.net/download
- Obtain the necessary Kickstart ROM files for the Amiga models you want to emulate.
- Make sure you have the appropriate game or software disk files (e.g., ADF, ADZ, DMS, IPF).

## Running a Game or Software

1. Clone the Git repository containing the FS-UAE configuration files.

2. Copy the Kickstart ROM files to the `kickstarts` folder.

3. Copy the game or software disk files to the `floppies` folder.

4. Launch FS-UAE from the command line with the desired configuration file:

```bash
fs-uae /path/to/config_file.fs-uae
```