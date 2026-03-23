# 🎮 Block Buster - Brick Breaker Game    


<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

**A modern, customizable brick breaker game built with vanilla JavaScript!**

[🎯 Quick Start](#-quick-start) • [📚 Learning Path](#-learning-path) • [🎮 Features](#-features) • [🚀 Deploy](#-deployment)

</div>

---

## 🎯 Quick Start

### Download & Play (30 seconds)

```bash
# Download these 3 files:
# 1. index.html
# 2. style.css
# 3. script.js

# Then open index.html in your browser
# And start playing!
```

### Controls
- **⬅️ ➡️ Arrow Keys** - Move paddle
- **🖱️ Mouse** - Track paddle to cursor
- **SPACE** - Pause/Resume

---

## 🎮 Features

### Core Gameplay
- ⚪ **Ball Physics** - Realistic bouncing and collision detection
- 🎯 **Paddle Control** - Smooth keyboard and mouse input
- 🧱 **8 Brick Patterns** - Random procedural level layouts
- 📊 **Score Tracking** - High scores saved in browser
- ❤️ **Lives System** - Start with 3 lives per game
- 🎨 **Particle Effects** - Visual feedback when destroying bricks

### Power-Ups
| Power-Up | Icon | Effect | Duration |
|----------|------|--------|----------|
| Multi-Ball | ⚫ | Duplicate balls (max 5) | 10s |
| Mega Paddle | 🛡️ | Double paddle width | 10s |
| Bullets | 🔫 | Auto-firing projectiles | 10s |

### Technical Features
- 💻 **No Dependencies** - Pure vanilla JavaScript
- 📱 **Responsive Design** - Works on desktop, tablet, mobile
- ⚡ **60 FPS** - Smooth gameplay on all devices
- 🎨 **CSS Variables** - Easy color theming and customization
- �� **Data Persistence** - High scores saved locally
- 🔒 **No Backend** - Everything runs in the browser

---

## 📁 Project Structure

```
block-buster-game/
├── index.html                  # Game structure (~4 KB)
├── style.css                   # Game styling (~8 KB)
├── script.js                   # Game logic (~35 KB)
└── README.md
```

---

## 🏗️ How It Works

### Game Loop
```javascript
function gameLoop() {
    update();      // Update ball, paddle, collisions
    render();      // Draw everything on canvas
    requestAnimationFrame(gameLoop);
}
```

### Key Systems
- **Ball Physics** - Velocity-based movement
- **Collision Detection** - AABB for rectangles, distance for circles
- **Power-Up System** - Time-based with duration tracking
- **Level Generation** - 8 procedural patterns
- **State Management** - Centralized gameState object

---

## 🌐 Browser Support

✅ Chrome (latest)  
✅ Firefox (latest)  
✅ Safari (latest)  
✅ Edge (latest)  
✅ Mobile browsers  

---

## 📊 Performance

- **FPS**: Consistent 60 FPS
- **File Size**: ~47 KB total (gzipped)
- **Dependencies**: Zero
- **Load Time**: Milliseconds

---

## 🤝 Contributing

Want to improve this course?

1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a Pull Request

### Contribution Ideas
- Add new tutorials
- Create new brick patterns
- Design new power-ups
- Improve documentation
- Add translations
- Fix bugs

---

## 📝 License

MIT License - completely free to use and modify!

### You can:
✅ Use for personal projects  
✅ Modify and customize  
✅ Share and distribute  
✅ Use commercially  


---
## 🎯 Roadmap

### Current (v1.0)
- ✅ 8 random level patterns
- ✅ 3 unique power-ups
- ✅ Score and high score tracking
- ✅ Responsive design
- ✅ 6-step learning path

### Planned (v2.0)
- 🔮 Sound effects and music
- 🔮 Particle systems
- 🔮 Achievement system
- 🔮 Difficulty progression
- 🔮 Mobile app
- 🔮 Multiplayer mode
---

<div align="center">

### Made with ❤️ by developers, for developers

**Let's build something awesome!** 🚀🎮

[License](LICENSE) • [Issues](https://github.com/sidd-harth/block-buster-game/issues) • [Discussions](https://github.com/sidd-harth/block-buster-game/discussions)

---

</div>
 
