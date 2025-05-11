# BomberQuestGame 🎮

**BomberQuestGame** is a 2D action-puzzle game developed using the **LibGDX** framework. In this game, players navigate a maze-like map, avoid enemies, destroy walls, and collect power-ups to reach the exit while solving challenges.

---

## 🛠️ Project Structure

```plaintext
oop-bomberman/
├── .gradle/               # Gradle-related files
├── .idea/                 # IntelliJ IDEA configuration files
├── assets/                # Game assets (textures, audio files, etc.)
├── core/
│   └── src/
│       └── main/
│           └── de.tum.cit.ase.bomberquest/
│               ├── audio/     # Sound and music handling
│               ├── map/       # Game map and entity logic
│               ├── screen/    # Screen and UI management
│               ├── texture/   # Texture and animation utilities
│               └── BomberQuestGame.java  # Main entry point
├── desktop/               # Desktop launcher for the game
├── maps/                  # Map configuration files
├── build.gradle           # Gradle build file
├── gradlew                # Gradle wrapper
├── gradlew.bat            # Gradle wrapper for Windows
├── README.md              # Project documentation (this file)
---

   ```
## 🚀 Getting Started

### Prerequisites
- **Java Development Kit (JDK)**: Version 8 or higher.
  - **Gradle**: Installed globally or use the Gradle Wrapper (`gradlew`).

### How to Run

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd oop-bomberman


2. **Import into IntelliJ IDEA**:
    - Open IntelliJ IDEA.
    - Select **File > Open...** and navigate to the project directory.
    - IntelliJ will automatically detect the Gradle project.

3. **Build the Project**:
   Run the following command in the terminal:
   ```bash
   ./gradlew build
   ```

4. **Run the Game**:
    - Open `DesktopLauncher.java` located in the `desktop` module.
    - Run it using IntelliJ IDEA or execute:
   ```bash
   ./gradlew desktop:run
   ```

## 🎮 Gameplay Instructions

### Objective
Reach the exit while defeating all enemies and collecting power-ups.

### Controls
- **Arrow Keys**: Move the player.
- **Spacebar**: Drop bombs to destroy walls and enemies.

### Power-Ups
- Increase bomb radius or allow more concurrent bombs.

### Enemies
- Avoid or eliminate them using bombs.

### Victory
- Unlock the exit by defeating all enemies and reach it to win.

## 🖼️ Assets

### Audio
- **Explosion Sound**: `audio/explosion.mp3`
- **Power-Up Sound**: `audio/powerup-pick-up.mp3`

### Textures
- **Player**: Animated movement textures.
- **Enemies**: Idle and animated textures.
- **Walls**: Destructible and indestructible.
- **Power-Ups**: Visual representation for bomb and radius boosts.

## 📂 Map Configuration

Maps are stored in the `maps` directory and are plain-text files defining the positions of walls, power-ups, enemies, and more.

### Example format:
```properties
1,1=0    # Indestructible wall
2,3=1    # Destructible wall
4,5=3    # Enemy
6,6=2    # Entrance
```

## 🛠️ Built With

- **LibGDX**: Cross-platform game development framework.
- **Gradle**: Build automation tool.

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## 🙌 Acknowledgments

- **Technical University of Munich (TUM)** for providing the project framework.
- Open-source libraries and resources used in the development process.

