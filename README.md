# To-Do-App-using Providers (state management)
# Simple To-Do List Application

## Overview

This is a minimalistic to-do list application built with Flutter, designed to help users manage tasks efficiently. Users can add, view, mark as complete, and delete tasks, with a reactive UI powered by the Provider package for state management. The app features a dark theme and a simple, intuitive interface, ensuring ease of use and responsiveness across devices.

---

## Features

### Task Management

- Add tasks with a title via a dedicated screen.
- View tasks in a list with completion status (strikethrough for completed tasks).
- Mark tasks as complete or incomplete using checkboxes.
- Delete tasks with a single tap.

### State Management

- Uses the Provider package for reactive updates when tasks are modified.

### Responsive Design

- Utilizes DevicePreview to test the UI on various screen sizes.
- Employs consistent padding and layout for a clean user experience.

### Modern UI

- Dark theme for a sleek, eye-friendly interface.
- Simple ListTile design with checkboxes and delete buttons for task interaction.

---

## Technologies Used

- **Flutter & Dart:** Cross-platform framework and programming language for building the app.
- **Packages:**
  - `flutter/material.dart`: For Material Design components.
  - [`provider`](https://pub.dev/packages/provider): For state management using the ChangeNotifier pattern.
  - [`device_preview`](https://pub.dev/packages/device_preview): For testing UI on different device sizes.

- **No Assets:** The app relies on Flutter’s built-in icons and widgets for a minimalistic design.

---

## Installation

```bash
# Clone the Repository
git clone https://github.com/yourusername/simple-todo.git

# Navigate to the Project Directory
cd simple-todo

# Install Dependencies
flutter pub get

# Run the App
flutter run

