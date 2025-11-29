# 🐱 Cat Volleyball

A fun and engaging 2D volleyball game featuring adorable cats as blocks, built with the Bevy game engine in Rust.

![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Bevy](https://img.shields.io/badge/bevy-0.10.1-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

## 🎮 About

Cat Volleyball is a physics-based volleyball game, implemented with the Bevy game engine in Rust, where two cats compete to keep the ball in the air. The game features realistic gravity physics, collision detection, and sound effects for an immersive gaming experience.

## ✨ Features

- **Two-Player Local Multiplayer**: Play against a friend on the same keyboard
- **Physics-Based Gameplay**: Realistic gravity and ball physics
- **Score Tracking**: Keep track of points for both players
- **Sound Effects**: Audio feedback for bounces and scoring
- **Background Music**: Enjoy continuous background music while playing

## 🎯 How to Play

### Controls

**Left Player (Cat 1)**
- `A` - Move left
- `D` - Move right

**Right Player (Cat 2)**
- `←` (Left Arrow) - Move left
- `→` (Right Arrow) - Move right

### Objective

Keep the ball from touching the ground on your side of the court. Each time the ball touches the ground, your opponent scores a point!

## 🚀 Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (latest stable version)
- Cargo (comes with Rust)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cat_volleyball.git
cd cat_volleyball
```

2. Build the project:
```bash
cargo build --release
```

3. Run the game:
```bash
cargo run --release
```

## 📁 Project Structure

```
cat_volleyball/
├── src/
│   └── main.rs          # Main game logic
├── assets/
│   ├── audio/           # Sound effects and music (*.ogg files)
│   ├── textures/        # Sprite sheets and images
│   └── fonts/           # Game fonts
├── Cargo.toml           # Project dependencies
└── README.md            # This file
```

## 🔧 Technical Details

### Built With

- **[Bevy](https://bevyengine.org/)** v0.10.1 - A refreshingly simple data-driven game engine
- **[Rand](https://docs.rs/rand/)** v0.9.1 - Random number generation for gameplay variance

### Game Components

- **Entity Component System (ECS)**: Leverages Bevy's powerful ECS architecture
- **Physics System**: Custom gravity and collision detection
- **Audio System**: Integrated sound effects and background music
- **Sprite Rendering**: Texture atlas-based sprite rendering

### Key Game Parameters

```rust
Arena Size: 800x600 pixels
Player Size: 22x32 pixels
Ball Radius: 4 pixels
Gravity: -40.0 units/s²
Player Speed: 60.0 units/s
```

## 🎨 Assets Required

To run the game, ensure you have the following assets in the `assets/` directory:

### Audio Files (`assets/audio/`)
- `bounce.ogg` - Ball bounce sound effect
- `score.ogg` - Scoring sound effect
- `Computer_Music_All-Stars_-_Albatross_v2.ogg` - Background music

### Textures (`assets/textures/`)
- `cat-sprite.png` - Sprite sheet containing cat and ball sprites (3x1 grid, 22x32 per sprite)

### Fonts (`assets/fonts/`)
- `square.ttf` - Font for score display

## 📝 Future Enhancements

- [ ] AI opponent for single-player mode
- [ ] Power-ups and special abilities
- [ ] Multiple difficulty levels
- [ ] Tournament mode
- [ ] Custom cat skins
- [ ] Online multiplayer support

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Built with [Bevy Engine](https://bevyengine.org/)
- Inspired by classic volleyball games
