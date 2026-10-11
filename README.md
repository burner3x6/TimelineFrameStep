# Timeline Frame Step

Adds keyboard shortcuts for frame-by-frame stepping in the [Timeline](https://github.com/Joan6694/Timeline) mod for Koikatsu Chara Studio.

## Features

- **← / →** to step one frame at a time (configurable)
- **Hold-to-repeat** — hold a key to continuously step
- **Configurable keys and repeat speed** via Configuration Manager

## Dependencies

- [BepInEx 5](https://github.com/BepInEx/BepInEx/releases)
- [Timeline](https://github.com/Joan6694/Timeline) by Joan6694
- [Configuration Manager](https://github.com/Bepis/ConfigManager) (for settings GUI — optional but recommended)

## Installation

1. Copy `TimelineFrameStep.dll` into `BepInEx/plugins/`
2. Launch Chara Studio
3. Open a scene, open the Timeline window
4. Use ← / → to step frames

## Configuration

Press **F1** in-game to open the Configuration Manager. Click the **"Plugins"** tab and look for **"Timeline Frame Step"**:

| Setting | Default | Description |
|---------|---------|-------------|
| Forward Key | `RightArrow` | Key to step forward. Any Unity KeyCode name (e.g. `D`, `PageUp`, `Period`) |
| Backward Key | `LeftArrow` | Key to step backward. Any Unity KeyCode name (e.g. `A`, `PageDown`, `Comma`) |
| Repeat Delay | `0.15` | Seconds between repeated steps while holding. Lower = faster |

To reset settings, delete `BepInEx/config/com.you.timelineframestep.cfg` and restart.

## Credits

- [Joan6694](https://github.com/Joan6694) — Timeline mod
- [BepInEx](https://github.com/BepInEx) — modding framework   
