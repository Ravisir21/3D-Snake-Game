# 🐍 3D Snake Game

A visually stunning, modern implementation of the classic Snake game with 3D effects, smooth animations, and immersive visuals - all in a single HTML file!

![Snake Game Screenshot](https://via.placeholder.com/800x400/0c1a2d/4cc9f0?text=3D+Snake+Game+Screenshot)
*Note: Add your own screenshot by replacing the placeholder URL*

## ✨ Features

- **🎮 Classic Snake Gameplay** - Navigate the snake to eat food and grow longer
- **🌟 3D Visual Effects** - Beautiful gradients, shadows, and particle effects
- **📊 Real-time Stats** - Track score, length, speed, and high score
- **⚙️ Multiple Difficulty Levels** - Easy, Normal, and Hard modes
- **🎵 Sound Effects** - Audio feedback for eating and game over
- **📱 Responsive Design** - Play on desktop, tablet, or mobile
- **💾 Persistent High Score** - Uses localStorage to save your best score
- **⏯️ Game Controls** - Pause, restart, and sound toggle options

## 🎯 How to Play

1. **Objective**: Control the snake to eat food (blue circles) and avoid collisions
2. **Controls**:
   - **Arrow Keys** or **WASD** to change direction
   - **P** key to pause/resume the game
   - **Spacebar** alternative pause button
3. **Scoring**:
   - Each food item: +10 points
   - Game speeds up as your score increases
   - Avoid walls and the snake's own body

## 🚀 Quick Start

Simply open the `index.html` file in any modern web browser!

**Option 1**: Clone the repository and open the file:
```bash
git clone https://Ravisir21/3d-snake-game.git
cd 3d-snake-game
open index.html  # Or double-click the file
```

**Option 2**: Download the single HTML file and open it directly in your browser

**Option 3**: Try it online at [Live Demo Link] (if hosted)

## 🛠️ Technologies Used

- **HTML5 Canvas** - For game rendering and animations
- **CSS3** - Modern styling with gradients, shadows, and responsive design
- **Vanilla JavaScript** - Game logic and interactivity (no frameworks!)
- **Web Audio API** - For sound effects
- **LocalStorage API** - For saving high scores
- **Font Awesome** - For icons

## 📁 Project Structure

```
3d-snake-game/
│
├── index.html          # The complete game (single file)
├── README.md           # This documentation file
└── (optional assets)   # Screenshots or additional files
```

## 🎨 Visual Features

### 3D Effects
- Snake segments with radial gradients and shadows
- Glowing food particles with animation
- Background particle system
- Smooth transitions and hover effects

### UI Elements
- Modern glass-morphism design
- Animated buttons with hover effects
- Real-time statistics display
- Clean game screens (start/game over)

### Game Visuals
- Grid-based play area with subtle lines
- Color-coded snake (head vs body)
- Direction-aware snake eyes
- Explosion effects on game over

## 🔧 Customization

You can easily customize the game by modifying these variables in the JavaScript section:

```javascript
// Change game speed (lower = faster)
let gameSpeed = 90;

// Change grid size
let gridSize = 20;

// Change colors in the CSS section
// Look for color variables like #4cc9f0, #2a5c9a, #0c1a2d
```

## 🎮 Game Modes

- **Easy**: Slowest speed, perfect for beginners
- **Normal**: Balanced speed for experienced players
- **Hard**: Fast-paced challenge for experts

## 📱 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Opera 50+

**Note**: Works best on modern browsers with hardware acceleration enabled.

## 🚫 Known Issues & Limitations

- Audio may be blocked by browser autoplay policies (click to enable)
- Performance may degrade on very old devices
- Touch controls not implemented (keyboard only)

## 🔮 Future Enhancements

Planned features for future versions:
- [ ] Touch controls for mobile devices
- [ ] Different food types with special effects
- [ ] Obstacles and power-ups
- [ ] Multiplayer mode
- [ ] Themes/skins selection
- [ ] Level progression system

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows the existing style and includes appropriate comments.

## 📝 Code Overview

### Main Functions
- `initGame()` - Initialize/reset game state
- `update()` - Main game loop with logic
- `draw()` - Render game elements to canvas
- `drawSnake()` - Draw snake with 3D effects
- `drawFood()` - Draw glowing food
- `gameOver()` - Handle end of game

### Key Variables
- `snake[]` - Array of {x, y} coordinates
- `food` - Current food position
- `direction` - Current snake direction
- `gameSpeed` - Controls game speed (lower = faster)
- `score`, `highScore` - Game statistics

## 🐛 Troubleshooting

**Game won't start?**
- Ensure JavaScript is enabled in your browser
- Check browser console for errors (F12)

**No sound?**
- Click the "Toggle Sound" button
- Check browser sound settings
- Some browsers require user interaction before playing audio

**Game is too slow/fast?**
- Adjust difficulty setting before starting
- Modify the `gameSpeed` variable in the code

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

MIT License gives you the freedom to:
- Use commercially
- Modify
- Distribute
- Sublicense
- Private use

All subject to including the original copyright and license notice.

## 🙏 Acknowledgments

- Inspired by the classic Nokia Snake game
- Thanks to the contributors of [Font Awesome](https://fontawesome.com/) for icons
- Gradient colors inspired by modern UI design trends
- Built with ❤️ for the developer community

## 📧 Contact

Your Name - [@Raviprakash](https://linkedin.com/in/Ravisir21) - myoffice1212.0@gmai.com

Project Link: [https://github.com/yourusername/3d-snake-game](https://github.com/Ravisir21/3d-snake-game)

---

**⭐ If you enjoy this game, please consider giving it a star on GitHub!**

---

*Made with pure HTML, CSS, and JavaScript - no frameworks, no dependencies!*