# Habits

An iOS habit tracking app built with SwiftUI focused on local-first data storage and high-density visual progress tracking.

## Overview

Habits is designed around fast daily logging and visual streak retention. It avoids cloud sync and accounts entirely, storing all historical metrics locally on device.

## Core Features

- Daily check-ins with progress rings for quantifiable metrics and binary completion for simple habits.
- 365-day contribution heatmaps showing daily consistency and frequency distribution.
- Streak and completion rate metrics calculated over 7-day, 30-day, and all-time windows.
- Flexible scheduling with weekday selection, custom target frequencies, and local reminders.
- Reorderable habit lists with custom iconography and color tagging.

## Interface Preview

| Daily Dashboard | Habit Heatmaps | Statistics | Customization |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/main.png" width="200"> | <img src="screenshots/heat.png" width="200"> | <img src="screenshots/stats.png" width="200"> | <img src="screenshots/edit.png" width="200"> |

## Technical Details

- Framework: SwiftUI
- Platform: iOS 17+
- Architecture: MVVM
- Storage: Local persistence (UserDefaults / JSON on-device storage)
- Graphics: Custom SwiftUI Canvas and Shape implementations for heatmaps and progress rings

---

The source code for this project is private. This repository serves as a showcase of the app's UI implementation and feature set.
