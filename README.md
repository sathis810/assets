# Curate Tool — Release Assets

This repository hosts the official pre-built installers for **Curate Tool**. Download the appropriate binary for your operating system and architecture below.

## Latest Release — v1.0.1

### Downloads

| Platform | Architecture | File | Download |
|----------|-------------|------|----------|
| **Windows** | x64 | `curate-tool-1.0.1.exe` | [Download](https://github.com/sathis810/assets/raw/main/curate/windows-build-x64/curate-tool-1.0.1.exe) |
| **Windows** | ARM64 | `curate-tool-1.0.1.exe` | [Download](https://github.com/sathis810/assets/raw/main/curate/windows-build-arm64/curate-tool-1.0.1.exe) |
| **macOS** | x64 (Intel) | `curate-tool-1.0.1.dmg` | [Download](https://github.com/sathis810/assets/raw/main/curate/mac-build-x64/curate-tool-1.0.1.dmg) |
| **macOS** | ARM64 (Apple Silicon) | `curate-tool-1.0.1.dmg` | [Download](https://github.com/sathis810/assets/raw/main/curate/mac-build-arm64/curate-tool-1.0.1.dmg) |
| **Linux** | x64 | `curate-tool-1.0.1.AppImage` | [Download](https://github.com/sathis810/assets/raw/main/curate/linux-build-x64/curate-tool-1.0.1.AppImage) |
| **Linux** | ARM64 | `curate-tool-1.0.1.AppImage` | [Download](https://github.com/sathis810/assets/raw/main/curate/linux-build-arm64/curate-tool-1.0.1.AppImage) |

## Installation

### Windows

1. Download the `.exe` file matching your architecture.
2. Run the installer and follow the on-screen prompts.

### macOS

1. Download the `.dmg` file matching your architecture.
2. Open the `.dmg` and drag **Curate Tool** into your Applications folder.

### Linux

1. Download the `.AppImage` file matching your architecture.
2. Make it executable:
   ```bash
   chmod +x curate-tool-1.0.1.AppImage
   ```
3. Run it:
   ```bash
   ./curate-tool-1.0.1.AppImage
   ```

## Repository Structure

```
curate/
├── linux-build-arm64/
│   └── curate-tool-1.0.1.AppImage
├── linux-build-x64/
│   └── curate-tool-1.0.1.AppImage
├── mac-build-arm64/
│   └── curate-tool-1.0.1.dmg
├── mac-build-x64/
│   └── curate-tool-1.0.1.dmg
├── windows-build-arm64/
│   └── curate-tool-1.0.1.exe
└── windows-build-x64/
    └── curate-tool-1.0.1.exe
```

## License

All rights reserved.
