# GameDev Assignment

A comprehensive Unity game development workspace containing assets, scripts, and resources for creating horror/survival games and FPS experiences.

## 📁 Project Structure

### Assets & Resources
- **`tools/`** - Main development resources directory
  - **`2025 Unity Files/`** - Current Unity project files
  - **`Models/`** - 3D models including weapons, props, and environment objects
  - **`Scripts/`** - C# scripts for game mechanics and systems
  - **`Sounds/`** - Audio files and sound effects
  - **`Textures/`** - Image assets and material textures
  - **`UI/`** - User interface elements and components

### Key Asset Collections

#### 🎮 Controllers & Systems
- **`FPS_Controllers/`** - First-person shooter controller implementations
- **`CameraUI - Full Systems/`** - Camera controls and UI overlays
- **`WeaponSystemFull/`** - Complete weapon system implementation

#### 🏗️ 3D Models & Assets
- **`Arms/`** - Character arm models with various textures (camo patterns, gloves)
- **`BasicHorrorGameAssets/`** - Complete horror game asset pack
- **`Models/`** - Various game objects including:
  - Weapons (Glock, M4, AR systems)
  - Props (doors, drawers, keypad, medical kit)
  - Attachments and modifications

#### 🎨 Visual Assets
- **`Textures/`** - Material textures and surface maps
- Camo patterns (Blue, Green, Red, White)
- Character customization options

## 🛠️ Core Game Systems

### Player Mechanics
- **Health System** (`PlayerHealth.cs`) - Player damage and death handling
- **Movement** - FPS controller with ladder climbing support
- **Interaction** (`PlayerReach.cs`, `LookAtObjects.cs`) - Object interaction system

### Gameplay Features
- **Inventory System** (`PickUpItems.cs`, `DragDropItem.cs`) - Item collection and management
- **Weapon System** (`WeaponsSwitch.cs`, `WeaponAttachments.cs`) - Weapon switching and customization
- **Flashlight System** (`Flashlight.cs`, `FlashlightAdvanced.cs`) - Lighting mechanics
- **Door System** (`Doors.cs`, `DoorsWithLock.cs`, `AdvancedDoors.cs`) - Interactive doors with locking mechanisms

### Environmental Systems
- **Lighting** (`LightSwitch.cs`, `LightsFlicker.cs`, `UseLight.cs`) - Dynamic lighting control
- **Power System** (`TurnPowerOn.cs`, `TurnPowerOff.cs`) - Electrical systems
- **Interactive Objects** (`OpenBoxScript.cs`, `OpenDrawer.cs`, `Keypad.cs`) - Environmental interactions

### UI & Interface
- **Main Menu** (`MainMenuLogic.cs`) - Game menu system
- **HUD Elements** (`HUD.cs`, `HealthBar.cs`) - In-game interface
- **Pause System** (`PauseGame.cs`) - Game state management
- **Camera Features** (`CameraZoom.cs`, `CameraUIZoom.cs`) - Camera controls

## 🎯 Game Types Supported

### Horror/Survival Games
- Slenderman-style gameplay mechanics
- Atmospheric lighting and sound systems
- Item collection and survival elements

### FPS Games
- Complete weapon systems
- Player health and damage mechanics
- Interactive environments

## 🚀 Getting Started

### Prerequisites
- Unity 2019.4 LTS or newer
- Basic understanding of C# scripting
- Unity Standard Assets (for FPS controller)

### Setup Instructions
1. Open Unity Hub
2. Add existing project and select the `tools/2025 Unity Files/` directory
3. Import any required Unity packages
4. Configure project settings as needed

### Key Scripts to Understand
1. **`MainMenuLogic.cs`** - Entry point for menu navigation
2. **`PlayerHealth.cs`** - Core player mechanics
3. **`FPS_Controllers/`** - Movement and camera control
4. **`WeaponsSwitch.cs`** - Weapon management system

## 📚 Learning Resources

This workspace appears to be designed for learning game development concepts including:
- Unity scripting fundamentals
- Game state management
- Player interaction systems
- 3D model integration
- Audio system implementation
- UI/UX design for games

## 🔧 Development Tools

### Included Utilities
- **`LimitFPS.cs`** / **`LockFPS.cs`** - Performance optimization
- **`Stopwatch.cs`** - Timing utilities
- **`Sway.cs`** - Weapon movement effects
- **`CompassImage.cs`** - Navigation helpers

### Performance Features
- FPS limiting and control systems
- Optimized lighting systems
- Efficient object spawning (`ObjectRandomSpawn1.cs`)

## 📝 Notes

- This appears to be an educational project focused on Unity game development
- Contains both beginner-friendly and advanced scripting examples
- Suitable for learning horror game mechanics and FPS development
- Includes complete asset pipelines from modeling to implementation

## 🎮 Tutorial Series

The workspace includes materials from various tutorial series:
- **Make A Game Series** - Step-by-step game development
- **Slenderman Clone Tutorial** - Horror game creation
- Multiple FPS controller implementations

---

*This README was generated for a Unity game development learning workspace. Modify and expand as your project grows!*
