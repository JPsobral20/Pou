# Pou AR – Augmented Reality Game

An augmented reality game inspired by the popular game Pou, developed using Unity. The project combines interactive gameplay, augmented reality, customization, dynamic weather conditions, and mini-games to create an immersive gaming experience.

## Overview

Pou AR brings the world of Pou into the real environment through augmented reality. Using the device's camera and marker-based tracking, players can interact with 3D objects and game elements placed in their surroundings.

The game features several interactive mechanics, allowing players to take care of Pou, customize its appearance, experience different weather conditions, and play mini-games.

## Features

### Augmented Reality
- Marker-based tracking using AR Foundation.
- Real-time placement and positioning of 3D objects in the physical environment.
- Interactive virtual objects integrated into the user's surroundings.

### Gameplay and Interactions
- Feed, clean, heal, and put Pou to sleep.
- Manage hunger, health, energy, and cleanliness.
- Monitor Pou's needs through visual indicators.
- Dynamic mood, appearance, and growth mechanics.

### Customization and Environment
- Equip Pou with different accessories, including sunglasses, a winter beanie, and a rain hat.
- Dynamic weather conditions that influence the environment and gameplay.
- Day and night lighting.
- Weather information retrieved through the Visual Crossing API.

### Mini-Games

**Maze**
- Navigate Pou through an augmented reality maze.
- Movement and collision detection mechanics.
- Interactive maze positioning.

**Memory**
- Memorize sequences of objects displayed to the player.
- Reproduce each sequence by delivering the correct objects to Pou.
- Progressively increasing difficulty through successive rounds.
- Audio feedback, countdowns, and score tracking.

## Technologies

- **Game Engine:** Unity 6
- **Programming Language:** C#
- **Augmented Reality:** AR Foundation, ARCore, ARKit
- **Interaction:** XR Interaction Toolkit
- **Rendering:** Universal Render Pipeline (URP)
- **UI:** TextMesh Pro
- **External API:** Visual Crossing Weather API

## Getting Started

### Prerequisites
- Unity Hub.
- Unity Editor 6.0.38f1.
- Android or iOS device with AR support.
- Corresponding AR platform packages and build modules.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/JPsobral20/Pou.git
   ```

2. Open Unity Hub.
3. Select **Add Project** and choose the cloned project directory.
4. Open the project using Unity 6.0.38f1.
5. Configure the appropriate platform settings (Android or iOS).
6. Build and deploy the application to a compatible device.

### Weather API Configuration

The project uses the Visual Crossing API to retrieve weather information. Configure your own API credentials in the `WeatherManager` component before running the application. Do not commit API keys or other credentials to the repository.

## Project Structure

- `Assets/Scripts/` – Gameplay logic, AR tracking, interactions, and mini-games.
- `Assets/Scenes/` – Main application and mini-game scenes.
- `Assets/Prefabs/` – Reusable game objects, interactive items, and 3D models.
- `Assets/Settings/` – Rendering and project configuration.
- `Packages/` – Unity package dependencies.
- `ProjectSettings/` – Unity editor and platform configuration.
