# Simple Timer

A minimalist macOS timer application that runs in both window and menu bar modes, perfect for work, study, cooking, or any activity that requires timing.

## Features

- ⏱️ Precise timing with hours, minutes, and seconds
- 🔄 Quick presets: 1m, 5m, 25m, and 60m with one click
- ⏯️ Complete control: start, pause, resume, reset, and stop functionality
- 🔔 Notifications: sound alerts and system notifications when timer completes
- 🖥️ Dual interface: main window and menu bar quick access
- 🏃‍♂️ Background operation: timer continues running when window is closed
- 🌙 Dark mode: full support for macOS dark mode
- 🔄 Menu bar display: shows remaining time while timer is running

## Technical Details

- Built with SwiftUI for macOS
- MVVM architecture with shared state
- Reactive programming using Combine framework
- System notifications and sound alerts
- Supports both menu bar and window application modes

## How to Use

### Basic Usage
1. Set your desired time using the hour, minute, and second pickers, or click a preset button (1m, 5m, 25m, 60m)
2. Click "Start" to begin the timer
3. Use the control buttons to pause, resume, reset, or stop the timer
4. When the timer completes, you'll receive both a sound notification and an alert

### Menu Bar Usage
1. Click the timer icon in the menu bar to open the timer
2. After setting and starting the timer, you can close the window and the timer will continue running in the background
3. The menu bar icon will display the remaining time
4. Right-click the menu bar icon to quit the application

## Requirements

- macOS 11.0 or later
- Compatible with both Intel and Apple Silicon processors

## Installation

1. Download the latest version of the application
2. Drag the app to your Applications folder
3. Double-click to launch

## Privacy

This application only requests notification permissions and does not collect any user data.