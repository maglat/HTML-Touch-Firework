# 🎆 HTML Touch Firework

A simple, lightweight firework animation triggered by click or touch. Perfect for adding some magic to any webpage!

## ✨ Features

- **Click & Touch** - Works on desktop and mobile
- **Auto-launch** - Fireworks launch automatically every few seconds
- **Rainbow colors** - Each firework has a random color
- **Particle physics** - Realistic gravity and friction effects
- **Lightweight** - Pure HTML5 Canvas, no dependencies
- **Performant** - Optimized particle count for smooth animation

## 🚀 Installation

1. Clone this repository:
```bash
git clone https://github.com/maglat/HTML-Touch-Firework.git
```

2. Open `index.html` in your browser
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

3. Or simply drag and drop the `index.html` file into your browser

## 🎮 Usage

- **Click** anywhere on the screen to launch a firework
- **Tap** on touch devices (mobile, tablet)
- Fireworks launch automatically every few seconds

## ⚙️ Configuration

Edit the `CONFIG` object in `index.html` to customize:

```javascript
const CONFIG = {
    particleCount: 35,        // Particles per explosion
    gravity: 0.08,            // How fast particles fall
    friction: 0.98,           // Air resistance
    baseSpeed: 6,             // Particle velocity
    fadeSpeed: 0.015,         // Fade out speed
    maxFireworks: 8,          // Max simultaneous fireworks
    autoFireworkInterval: 5000 // Auto-launch interval (ms)
};
```

## 👨‍💻 Author

Created with ❤️ by [maglat](https://github.com/maglat)

Enjoy the show! 🎆✨