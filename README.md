# MEGA MACRO V1.0

A lightweight Windows overlay macro for game training mini-games. It detects on-screen letters, presses the matching keys, and pauses or resumes automatically based on your mana or stamina bar.

## Download

Download the latest **`MEGA MACRO.exe`** from the [Releases](../../releases) page.

The application is distributed as a Windows executable. No separate Python installation is intended to be required for end users.

## Installation

1. Download `MEGA MACRO.exe` from Releases.
2. Run the executable.
3. Follow the installation prompts.
4. Activate the application using your license key.
5. Open your game and check for the overlay.

## Features

- **Always-on-top overlay:** Designed to remain visible over the game window.
- **Automatic letter detection:** Uses template and shape matching.
- **Mana and stamina monitoring:** Pauses when the bar is low and resumes when it refills.
- **Multiple training modes:** Jumping rope, pushup, squat, handstand pushup, bicycle crunch, situp, and kettlebell pistol squat.
- **Sound effects:** Audio feedback during use.
- **Adjustable stamina slider:** Configure the stamina threshold.
- **Power menu:** Access controls with a right-click menu.
- **Offline licensing:** License activation works offline.
- **Hardware-locked activation:** Each license key is intended for one PC.

## License System

MEGA MACRO uses an offline, hardware-locked licensing system. Each license key is intended to activate the software on a single PC.

Keep your license key private. Do not publish private activation data, license-generation secrets, or signing keys.

## System Requirements

- Windows
- A compatible game and display configuration
- A valid MEGA MACRO license key

## Build from Source

The following commands can be used to install the listed Python dependencies and run the release build script, provided the source files are available:

```bash
pip install mss numpy opencv-python pillow pydirectinput pyinstaller
python build_release.py
```

The build script and required source files must be included separately for this process to work.

## Disclaimer

Use the software responsibly and follow the rules of the games you play. Compatibility and detection accuracy may vary by game and display settings.
