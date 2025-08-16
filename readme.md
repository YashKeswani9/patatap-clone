# Patatap Clone

An interactive musical art experience inspired by [Patatap](https://patatap.com). Create beautiful visual animations with corresponding sound effects by pressing keys on your keyboard.

## Demo

🎵 **[Live Demo](your-deployment-link-here)** | 🎨 [Original Patatap](https://patatap.com)

## Features

- **Interactive Audio-Visual Experience** - Each keypress creates unique animations paired with sound
- **Responsive Design** - Works on desktop and mobile devices
- **Smooth Animations** - Fluid visual effects using Paper.js
- **High-Quality Audio** - Crystal clear sound effects with Howler.js
- **26 Unique Combinations** - Different animation and sound for each letter key

## Tech Stack

- **HTML5** - Structure and canvas element
- **CSS3** - Styling and responsive design
- **JavaScript** - Core interaction logic
- **Paper.js** - Vector graphics and animation library
- **Howler.js** - Web audio library for sound management

## Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- Local web server (recommended) or simply open `index.html`

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/patatap-clone.git
```

2. Navigate to the project directory
```bash
cd patatap-clone
```

3. Open `index.html` in your browser or serve with a local server
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have live-server installed)
live-server

# Or simply open index.html in your browser
```

## How to Use

1. Open the application in your browser
2. Press any letter key (A-Z) on your keyboard
3. Watch as each key creates a unique visual animation with accompanying sound
4. Experiment with different key combinations and timing for varied effects

## Project Structure

```
patatap-clone/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── patatap.css     # Styles and animations
│   └── js/
│       └── lib/
│           └── paper-full.js # Paper.js library (local)
├── sounds/                 # Audio files directory
└── README.md              # This file
```

## Key Features Implemented

- **Keyboard Event Handling** - Responsive to keypress events
- **Canvas Animation** - Smooth vector animations using Paper.js
- **Audio Management** - Seamless sound playback with Howler.js
- **Visual Effects** - Dynamic shapes, colors, and motion
- **Performance Optimization** - Efficient rendering and memory management

## Future Enhancements

- [ ] Mobile touch support for on-screen keyboard
- [ ] Custom sound upload functionality
- [ ] Recording and playback of compositions
- [ ] Additional visual effect patterns
- [ ] Volume and visual intensity controls

## Credits

- Inspired by [Patatap](https://patatap.com) by Jono Brandel
- Built with [Paper.js](http://paperjs.org/) for graphics
- Audio powered by [Howler.js](https://howlerjs.com/)

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This is a learning project created to explore interactive web audio and canvas animations. All credit for the original concept goes to the creators of Patatap.