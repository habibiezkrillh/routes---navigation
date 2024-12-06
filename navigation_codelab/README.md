# Navigation Codelab (With Additional Advanced Navigation)

A Flutter application demonstrating basic navigation between screens using named routes.

## Getting Started

This project is a Flutter application that shows how to implement navigation between multiple screens.

### Prerequisites

Before running this application, make sure you have the following installed:

- [Flutter](https://flutter.dev/docs/get-started/install) (Latest stable version)
- [Dart](https://dart.dev/get-dart)
- An IDE (VS Code, Android Studio, or IntelliJ)
- Android Emulator (in this task i only use Chrome for running the app, press [`2`] to run from Chrome)

### Installation

1. Clone this repository: https://github.com/habibiezkrillh/routes---navigation.git
2. Using VSCode or other IDE that you use
   - Open the project in your IDE
   - Press F5 to run or,
   - Go to the terminal and type `flutter run`
3. And then you have it a simple application with route and navigation

## Application Structure
This App consist of three main files:
- `lib/main.dart`: Contains the app initialization and route configuration
- `lib/first_screen.dart`: The initial screen of the app
- `lib/second_screen.dart`: The second screen that can be navigated to first screen

## Usage

The application demonstrates a simple navigation flow:

1. When the app launched, the app shows the First Screen
2. Users can navigate to the Second Screen using the navigation button
3. From the Second Screen, users can return to
   - The `Go Back` button in the app bar
   - The navigation button (drawer) on the screen
4. There's a Drawer the function is for navigation to First Screen or even Second Screen

## Why im only use Drawer

Simply because when i try to code for bottom navigation bar it and when i run it, the bottom navigation bar is messy. So that's why i only use the Drawer for make it easy navigation to the First Screen or even the Second Screen.
