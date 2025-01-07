# Hammerspoon Configuration

> Hammerspoon: because sometimes automating your Mac requires a real hammer! 

This repository contains my personal Hammerspoon configuration for window management and keyboard shortcuts. Hammerspoon is a powerful automation tool for macOS that allows you to write Lua scripts to control various aspects of your system.

## Features

### Window Management

This configuration provides comprehensive window management capabilities with the following features:

- Resize windows to screen halves
- Resize windows to screen thirds (both horizontal and vertical)
- Move windows between screens
- Center windows
- Maximize windows

## Keyboard Shortcuts

### Screen Halves
- `Ctrl + Cmd + Left`: Move window to left half
- `Ctrl + Cmd + Right`: Move window to right half
- `Ctrl + Cmd + Up`: Move window to top half
- `Ctrl + Cmd + Down`: Move window to bottom half

### Screen Thirds
- `Ctrl + Alt + Left`: Cycle through left thirds
- `Ctrl + Alt + Right`: Cycle through right thirds
- `Ctrl + Alt + Up`: Cycle through top thirds
- `Ctrl + Alt + Down`: Cycle through bottom thirds

### Window Controls
- `Ctrl + Cmd + C`: Center window on screen
- `Ctrl + Alt + Cmd + F`: Maximize window
- `Ctrl + Alt + Cmd + Up`: Maximize window (alternative)

### Multi-Screen Controls
- `Ctrl + Alt + Cmd + Left`: Move window to left screen
- `Ctrl + Alt + Cmd + Right`: Move window to right screen

## Installation

1. Install Hammerspoon:
   ```bash
   brew install --cask hammerspoon
   ```

2. Clone this repository to your Hammerspoon configuration directory:
   ```bash
   git clone https://github.com/yourusername/hammerspoon-config.git ~/.hammerspoon
   ```

3. Launch Hammerspoon and enable accessibility permissions when prompted

## Usage

After installation, you can use any of the keyboard shortcuts listed above to manage your windows. The configuration will automatically load when Hammerspoon starts, and you'll see a notification saying "Hammerspoon Config Loaded".

To reload the configuration at any time, click the Hammerspoon menubar icon and select "Reload Config".