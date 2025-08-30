# 🚗 Cop Chase Game

A thrilling dice-rolling chase game where you must escape from the police in a procedurally generated city! Built with vanilla HTML5, CSS3, and JavaScript with enhanced mobile optimization.

![Game Preview](https://via.placeholder.com/800x400/1a1a2e/ffffff?text=Cop+Chase+Game+Preview)

## 🎮 Game Features

- **🎲 Dice-Based Movement**: Roll dice to move your car through the city
- **🚔 Smart Police AI**: Police cars that chase you using intelligent pathfinding
- **🏙️ Procedural City Generation**: Each game features a unique city layout with optimized grid size
- **🚦 Traffic Light System**: Red lights stop players but police ignore them
- **📱 Mobile Optimized**: Enhanced responsive design with centered controls and improved touch targets
- **🗺️ Map Editor**: Create and test your own custom maps with mobile-friendly interface
- **🎵 Background Music**: Immersive audio experience
- **🌟 Modern UI**: Beautiful glassmorphism design with enhanced blur effects and smooth animations

## 🚀 How to Play

1. **🎲 Roll the Dice**: Click the golden dice button to roll and move
2. **🚗 Choose Direction**: At intersections, select your path (straight, left, or right)
3. **🚦 Obey Traffic Rules**: Stop at red lights (police don't follow this rule!)
4. **🚔 Avoid the Police**: Stay away from police cars - they're chasing you!
5. **🛣️ Stay on Roads**: You can only drive on roads and intersections
6. **🎯 Survive**: The goal is to survive as long as possible!

## 🎮 Controls

### Desktop
- **Mouse**: Click dice button to roll, click direction buttons to choose path
- **Keyboard**: Game is designed for mouse interaction

### Mobile
- **Touch**: Tap dice button to roll, tap direction buttons to navigate
- **Portrait Mode**: Optimized for mobile portrait orientation
- **Enhanced Controls**: Larger, centered direction buttons with improved touch targets
- **Glassmorphism UI**: Enhanced blur effects matching desktop version for better visual hierarchy

## 🗺️ Map Editor

Create your own custom maps with the built-in editor:

- **🎨 Multiple Terrain Types**: Roads, intersections, traffic lights, buildings, lakes
- **🔧 Easy Tools**: Paint brush system for quick map creation
- **💾 Save & Load**: Save your maps and share them
- **🧪 Test Mode**: Test your maps before saving

### Terrain Types
- **🔄 Vertical Roads**: North-south traffic flow
- **↔️ Horizontal Roads**: East-west traffic flow  
- **✕ Intersections**: Road crossings
- **🚦 Traffic Lights**: Controlled intersections
- **🟫 Land**: Various building types
- **🟩 Grass**: Residential areas with trees
- **🏭 Industrial**: Factory and office buildings
- **🟤 Brown Soil**: Rural areas
- **🟨 Desert**: Sandy terrain
- **⛰️ Rocky**: Mountainous terrain
- **💧 Lakes**: Water bodies

## 🛠️ Installation & Setup

### Quick Start
1. Clone the repository:
```bash
git clone https://github.com/yourusername/cop-chase-game.git
cd cop-chase-game
```

2. Open the game:
```bash
# Simply open index.html in your web browser
open index.html
# or
python -m http.server 8000  # For local server
```

3. Start playing! 🎮

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required
- Audio file support for background music

## 📁 Project Structure

```
cop-chase-game/
├── index.html          # Main game file
├── CopChase_cut.mp3    # Background music (optional)
├── README.md           # This file
└── assets/             # Game assets (if any)
```

## 🎯 Game Mechanics

### Player Movement
- Roll dice (1-6) to determine movement distance
- Choose direction at intersections
- Must stay on roads and intersections
- Stopped by red traffic lights

### Police Behavior
- 2 police cars spawn at game start
- Move after each player turn
- Use pathfinding to chase the player
- Ignore traffic lights and terrain restrictions
- Game ends if they catch the player

### Map Generation
- 14×24 grid optimized for mobile performance and visibility
- Procedural road network with perimeter roads
- Internal road grid every 3×5 cells
- Random terrain features (lakes, buildings, trees)
- Traffic lights at major intersections
- Enhanced mobile rendering with optimized cell sizes

## 🎨 Technical Features

### Frontend Technologies
- **HTML5**: Semantic structure and audio support
- **CSS3**: Modern styling with glassmorphism effects
- **JavaScript ES6+**: Game logic and interactive features

### Design Patterns
- Object-oriented game architecture
- Responsive design with mobile-first approach
- Progressive enhancement for touch devices

### Performance Optimizations
- Efficient DOM manipulation
- Smooth animations with CSS transforms
- Touch-optimized controls for mobile
- Minimal memory footprint

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **🐛 Bug Reports**: Open an issue with detailed steps to reproduce
2. **💡 Feature Requests**: Suggest new features or improvements  
3. **🔧 Code Contributions**: Fork, create a feature branch, and submit a PR
4. **🗺️ Map Sharing**: Share your custom maps with the community
5. **📖 Documentation**: Help improve documentation and tutorials

### Development Setup
```bash
# Fork the repository
git clone https://github.com/yourusername/cop-chase-game.git
cd cop-chase-game

# Create a feature branch
git checkout -b feature/your-feature-name

# Make your changes and test
# Open index.html in browser to test

# Commit and push
git commit -m "Add your feature description"
git push origin feature/your-feature-name

# Create a Pull Request
```

## 📊 Game Statistics

- **Grid Size**: 14×24 cells (optimized for mobile performance and visibility)
- **Cell Size**: Dynamic (16-24px based on screen size for better mobile performance)
- **Police Count**: 2 AI-controlled units
- **Terrain Types**: 11 different terrain types
- **Traffic Lights**: 40% spawn rate at internal intersections
- **Mobile Optimization**: Enhanced touch targets and centered control positioning

## 🎵 Audio

The game includes optional background music. To add audio:

1. Place `CopChase_cut.mp3` in the same directory as `index.html`
2. The game will automatically load and play background music
3. Players can toggle music on/off with the music button

## 📱 Mobile Optimization

- **Enhanced Responsive Design**: Adapts to all screen sizes with optimized grid dimensions
- **Centered Touch Controls**: Direction buttons positioned at screen center for better accessibility
- **Improved Touch Targets**: Larger buttons (110px minimum width) with increased padding for easier interaction
- **Glassmorphism Consistency**: Enhanced blur effects (25px backdrop-filter) matching desktop version
- **Portrait Mode**: Optimized 14×24 grid for better performance in portrait orientation
- **Performance**: Smooth 60fps animations on mobile devices with reduced grid complexity
- **Battery Friendly**: Efficient resource usage with optimized cell count
- **Enhanced Visual Hierarchy**: Consistent blur effects and transparency across all UI elements

## 🏆 High Score System

Currently, the game tracks:
- **Move Count**: Number of dice rolls survived
- **Survival Time**: How long you avoided capture
- **Map Completion**: Successfully navigating different map layouts

*Future updates may include persistent high scores and leaderboards.*

## 🐛 Known Issues

- Background music requires user interaction to start (browser policy)
- Some older mobile browsers may have performance limitations
- Map editor requires desktop/tablet for optimal experience

## 📈 Roadmap

### Version 2.0 (Planned)
- [ ] Persistent high score system
- [ ] Multiple difficulty levels
- [ ] Power-ups and special abilities
- [ ] Multiplayer support
- [ ] Achievement system
- [ ] Custom car selection
- [ ] Advanced mobile gestures support

### Version 1.5 (In Progress)
- [x] Enhanced mobile UI with centered controls
- [x] Improved glassmorphism effects
- [x] Optimized grid size for better mobile performance
- [ ] Enhanced AI for police
- [ ] More terrain types
- [ ] Sound effects
- [ ] Tutorial mode

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic chase games and board games
- Built with modern web technologies
- Special thanks to the open-source community
- Emoji icons from Unicode standard

## 📞 Support

- **🐛 Bug Reports**: [Open an Issue](https://github.com/Pijamka88/cop-chase-game/issues)
- **💬 Discussions**: [GitHub Discussions](https://github.com/Pijamka88/cop-chase-game/discussions)
- **📧 Contact**: your.email@example.com

---

**🎮 Ready to play? Clone the repo and start your escape!**

Made with ❤️ and lots of ☕
