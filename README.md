# TeknoParrotUI-H2O

Open Source JVS / Other I/O emulator for Windows. Works with [OpenParrot-H2O](https://github.com/ProjectH2O/OpenParrot) and [H2ODashboard](https://github.com/ProjectH2O/H2ODashboard).

This is a component of [Project H2O](https://github.com/ProjectH2O/ProjectH2O), not intended for standalone use. Please see the Project H2O page for details.

### Changes

- Supports H2Overdrive only
- No internet access: removed updater, TeknoParrot Online, Patreon, Discord Rich Presence, icon downloads, mods menu
- H2Overdrive-specific settings:
  - Display mode: Borderless, Windowed or Fullscreen
  - Resolution (0 = desktop)
  - 60 FPS limit and VSync off
  - Network adapter choice for LAN play
  - Force End Race key
  - Debug Log
- Library cleanup: removed the "More info" button and the Test Menu switch, which H2Overdrive can't use
- Links point to ProjectH2O
- New defaults: dark mode on, exit confirmation off, holiday themes off
- .NET Framework 4.8 instead of 4.6.1, and Score Submission removed (both from the [Project Asakura fork](https://github.com/ProjectAsakura/TeknoParrotUI))
