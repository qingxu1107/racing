# Neon Racer

A fast-paced, Y8-style arcade racing game built with HTML5 Canvas and JavaScript. Dodge traffic, survive as long as possible, and beat your high score!

## Play Now

Simply open `neon-racer.html` in any modern web browser. No installation required!

## How to Play

### Controls
- **Arrow Keys** (← →) or **A/D** - Move left/right between lanes
- **Spacebar** or **Click** - Start/Restart game

### Objective
- Dodge oncoming traffic cars
- Survive as long as possible
- Score increases with distance and time
- Beat your high score!

## Features

### Gameplay
- **3-Lane Highway** - Navigate through traffic in three lanes
- **Progressive Difficulty** - Speed increases as your score grows
- **Traffic AI** - Cars spawn randomly with varying speeds
- **Collision Detection** - Game ends on impact with traffic
- **Particle Effects** - Explosion animation on crash

### Visual Style (Y8 Inspired)
- **Neon Glow Effects** - Cyan, magenta, and yellow color scheme
- **Retro Arcade Aesthetic** - Inspired by classic arcade racers
- **Glowing UI Elements** - Score, speed, and buttons with neon shadows
- **Animated Start/Game Over Screens** - Pulsing and gradient animations
- **Smooth Lane Transitions** - Fluid car movement

### Technical Features
- **High Score Persistence** - Saves best score using localStorage
- **60 FPS Game Loop** - Smooth gameplay using requestAnimationFrame
- **Responsive Design** - Works on desktop browsers
- **No Dependencies** - Pure HTML5 Canvas + Vanilla JavaScript
- **Lightweight** - Single HTML file, less than 10KB

## Game Mechanics

### Scoring System
- **Distance Points** - Earn points based on distance traveled
- **Overtake Bonus** - +10 points for each car passed
- **Speed Multiplier** - Higher speeds = faster score accumulation

### Difficulty Scaling
- **Base Speed** - Starts at comfortable pace
- **Speed Increase** - Every 500 points adds speed
- **Spawn Rate** - Traffic spawns more frequently as you progress
- **Max Speed Cap** - Speed capped at 20x multiplier (200 km/h display)

## Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- Opera 47+

## File Structure

```
neon-racer.html          # Complete game (HTML + CSS + JS)
README.md                # This file
```

## Technical Details

### Built With
- **HTML5 Canvas** - 2D rendering context
- **CSS3** - Animations, gradients, and neon effects
- **Vanilla JavaScript** - No frameworks or libraries
- **localStorage API** - High score persistence

### Game Architecture
- **Game Loop** - requestAnimationFrame-based loop
- **Entity System** - Player car and traffic car objects
- **Particle System** - Dynamic explosion effects
- **Input Handling** - Keyboard event listeners
- **State Management** - Game states: start, playing, game over

## Tips & Tricks

1. **Plan Ahead** - Watch for traffic patterns 2-3 cars ahead
2. **Stay Center** - Middle lane offers most escape options
3. **Speed Management** - Higher speed = more points but harder to dodge
4. **Quick Reflexes** - Lane changes happen smoothly but plan early
5. **Pattern Recognition** - Traffic tends to cluster, look for gaps

## Development

### Future Enhancements
- Power-ups (shield, speed boost, slow motion)
- Multiple car colors/skins
- Sound effects and music
- Mobile touch controls
- Online leaderboard
- Different game modes (time trial, endless, challenge)

### Customization

To modify the game, edit the JavaScript section in `neon-racer.html`:

```javascript
// Adjust difficulty
const lanes = 3;                    // Number of lanes (2-5)
let baseSpeed = 5;                  // Starting speed
let spawnInterval = 60;             // Traffic spawn rate

// Change colors
const trafficColors = ['#ff0066', '#ff00ff', '#ffff00'];
player.color = '#00ffff';           // Player car color

// Canvas size
const canvas = document.getElementById('gameCanvas');
canvas.width = 600;                 // Game width
canvas.height = 800;                // Game height
```

## License

This project is open source and available for personal and educational use.

## Credits

- **Game Design** - Inspired by Y8.com racing games
- **Visual Style** - Neon/cyberpunk arcade aesthetic
- **Built by** - AI Assistant (Claude)

## Support

If you encounter any issues:
1. Ensure you're using a modern browser
2. Check that JavaScript is enabled
3. Try refreshing the page
4. Clear browser cache if high scores aren't saving

---

**Enjoy the ride!** 🏎️💨

*High scores are saved locally in your browser.*
