# Lumma Overlay

<p align="center">
  <strong>In-game monitor control overlay — no alt-tabbing required.</strong>
</p>

<p align="center">
  <a href="https://github.com/Bob3111/lumma-overlay/releases/latest">
    <img src="https://img.shields.io/github/v/release/Bob3111/lumma-overlay?label=version&color=00D4FF" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey" alt="Platform">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white" alt="Windows">
</p>

<p align="center">
  <strong>Control your monitor brightness, contrast, gamma, color temperature and more — directly from inside any game.</strong>
</p>

---

## What is Lumma Overlay?

Lumma Overlay is a lightweight, transparent overlay that sits on top of your games and lets you adjust your monitor settings in real-time — **without ever leaving your game**.

Built for gamers who want to fine-tune their display on the fly, whether it's darkening a scene in a horror game, boosting contrast in competitive shooters, or adjusting color temperature for late-night sessions.

---

## Features

| Feature | Description |
|---------|-------------|
| Real-time Monitor Control | Adjust brightness, contrast, gamma, color temperature, saturation, and more via DDC/CI |
| Auto Game Detection | Automatically detects when you enter/exit fullscreen games |
| FPS Counter | Real-time FPS overlay using Intel PresentMon ETW capture |
| Per-Game Profiles | Save settings per game and auto-load when you launch |
| Xbox Controller Support | Full D-Pad navigation — no keyboard needed |
| Quick Presets | One-click brightness/contrast presets for common scenarios |
| Compact Mode | Minimal overlay that stays out of your way |
| Auto-Launch | Starts with Windows automatically |
| Tray Menu | Full control from the system tray icon |
| Update Checker | Automatically checks for new releases |

---

## Keyboard Controls

| Hotkey | Action |
|--------|--------|
| `Ctrl + Shift + O` | Toggle overlay visibility |
| `Ctrl + Shift + Up` | Brightness +5% |
| `Ctrl + Shift + Down` | Brightness -5% |
| `Ctrl + Shift + Right` | Contrast +5% |
| `Ctrl + Shift + Left` | Contrast -5% |
| `Ctrl + Shift + R` | Reset to defaults |
| `Ctrl + Shift + P` | Cycle through profiles |

---

## Xbox Controller

| Button | Action |
|--------|--------|
| **View + Select** (hold) | Open/close controller mode |
| **D-Pad Up** | Move selection up |
| **D-Pad Down** | Move selection down |
| **D-Pad Left** | Decrease selected value |
| **D-Pad Right** | Increase selected value |

> The overlay automatically detects when you're in a game and switches to controller mode seamlessly.

---

## Installation

1. **Download** the latest installer from the [Releases](https://github.com/Bob3111/lumma-overlay/releases/latest) page
2. **Run** `Lumma_Overlay_Setup_1.1.0.exe` as Administrator
3. **Follow** the installation wizard
4. **Launch** from your Desktop or Start Menu

> The app requires Administrator privileges to communicate with monitors via DDC/CI and capture FPS data.

---

## Settings & Options

### Interface Options
- **Compact Mode** — Reduces overlay size for minimal screen coverage
- **Show Quick Presets** — Toggle the presets bar visibility
- **Show Profile Section** — Toggle the profile selector visibility
- **Transparency** — Adjust overlay opacity from 35% to 100%

### Profiles
- Create custom profiles for different games or scenarios
- Auto-load profiles when a specific game is detected
- Export and share profiles with other users

### Monitor Selection
- Select which monitor to control (multi-monitor setups supported)
- Apply settings globally or per-monitor

### Auto-Launch
- Toggle "Start with Windows" from the tray menu or Settings > About
- Runs silently in the background, ready when you need it

---

## How It Works

Lumma Overlay uses two main technologies:

### DDC/CI Protocol
The app communicates with your monitor using the **Display Data Channel / Command Interface** protocol — the same standard used by monitor manufacturer software. This allows hardware-level control of brightness, contrast, and other settings directly through your display cable (HDMI/DisplayPort).

### PresentMon FPS Capture
FPS data is captured using **Intel PresentMon**, an open-source tool that uses Windows Event Tracing (ETW) to measure frame timing with sub-millisecond accuracy. This gives you real-time, accurate FPS readings without any performance impact.

---

## Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10 or Windows 11 |
| **Monitor** | DDC/CI compatible (most modern monitors) |
| **Game Mode** | Borderless windowed recommended for overlay visibility |
| **Permissions** | Administrator (required for DDC/CI and FPS monitoring) |

> DDC/CI must be enabled in your monitor's OSD settings. Most monitors have this enabled by default.

---

## Changelog

### v1.1.0 — First Release
- Full DDC/CI monitor control (brightness, contrast, gamma, color temp, saturation)
- Auto game detection with per-game profiles
- FPS counter via PresentMon
- Xbox controller support (D-Pad navigation)
- Quick presets system
- Compact mode
- Auto-launch with Windows
- Full tray menu control
- Update checker
- Profile save/load/export system

---

## Security & Privacy

- **No telemetry** — Lumma Overlay does not collect or send any data
- **No internet required** — Works fully offline (update check is optional)
- **Zero external dependencies** — Everything is bundled in the installer
- **Compiled & obfuscated** — All code is compiled and obfuscated for security

---

<p align="center">
  Made with ❤️ by <strong>MCO</strong>
</p>

<p align="center">
  <a href="https://github.com/Bob3111/lumma-overlay/releases/latest">Download Latest Release</a>
</p>
