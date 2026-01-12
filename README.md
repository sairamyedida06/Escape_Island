# 📱 Escape_Island

A fully optimized **Android 3D Platformer** developed in Unreal Engine 5. This project demonstrates a complete mobile game loop, featuring character selection, progressive level unlocking, and performance-optimized assets.

## 🛠 Technical Implementation (C++ & Blueprints)
This project uses a **hybrid workflow** to balance performance and development speed:

* **C++ Implementation:**
    ** Created C++ classes for **Moving and Rotating Platforms** to ensure smooth, tick-efficient updates on mobile hardware.
* **Blueprint Implementation:**
    * **Game Logic:** Handles the coin collection system, save/load functionality, and level management.
    * **Simple AI:** Custom distance-based Enemy AI (designed without Behavior Trees for lower overhead).
    * **UI System:** Full menu flow including Main Menu, Character Selection, Level Select, Pause, and Death screens.

## 🎮 Gameplay Features
* **4 Unique Levels:** Progressive difficulty; Level 2 unlocks only after completing Level 1.
* **Save System:** Persistent data tracks unlocked levels and high scores.
* **Character Selection:** Menu system allowing players to choose different avatars.
* **Mobile Optimization:** Built with low-poly assets and optimized materials to ensure smooth performance on Android devices.

## 🚀 How to Run
1.  Clone the repository.
2.  Right-click the `.uproject` file and select **Generate Visual Studio project files**.
3.  Build the solution in Visual Studio (Development Editor).
4.  Open the project 
