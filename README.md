#  Rabbit Game: Hop & Collect

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Love](https://img.shields.io/badge/Made%20with--red.svg)](https://github.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A delightful and challenging grid-based arcade game where you control a hungry rabbit  collect crunchy carrots , and outsmart a sneaky fox !



##  Table of Contents
- [About the Game](#-about-the-game)
- [How to Play](#-how-to-play)
- [Features](#-features)
- [Gameplay Mechanics](#-gameplay-mechanics)
- [Technologies Used](#-technologies-used)
- [Installation & Local Setup](#-installation--local-setup)
- [Controls](#-controls)
- [Customization Ideas](#-customization-ideas)
- [License](#-license)
- [Contributing](#-contributing)
- [Acknowledgments](#-acknowledgments)

##  About the Game

**Rabbit Game** is a fast-paced, tactical collection game built entirely with vanilla HTML, CSS, and JavaScript. Guide your rabbit across a lush 20x12 grid, gather as many carrots as possible, and avoid the patrolling fox that gets smarter and hungrier with every hop!

The game combines nostalgia with modern web standards — no external libraries, no frameworks, just pure browser fun.

##  How to Play

1. **Start the game** – The rabbit and fox are placed on a grassy field with carrots scattered around.
2. **Move your rabbit** – Use the **arrow keys** or **on-screen buttons** to hop up, down, left, or right.
3. **Collect carrots** – Each carrot you touch adds +1 to your score and a new carrot spawns somewhere else.
4. **Avoid the fox** – The fox moves toward you every 0.55 seconds. If it lands on your rabbit, it's **GAME OVER**!
5. **Keep collecting** – The game continues until the fox catches you. Try to beat your high score!

##  Features

-  **Cute pixel-style graphics** – Hand-drawn rabbit, fox, and carrot illustrations using Canvas API.
-  **Adaptive AI** – The fox uses Manhattan distance to chase the rabbit intelligently.
-  **Dynamic Carrot System** – Carrots respawn after being collected to keep the game alive.
-  **Dual Controls** – Play with keyboard arrows or on-screen touch-friendly buttons.
-  **Responsive Design** – Works on desktop, tablet, and mobile devices.
-  **Instant Restart** – Reset the game anytime with the RESTART button.
-  **Visual Feedback** – Score updates, game over overlay, and status messages.
-  **Movement Cooldown** – Prevents turbo-moving and keeps gameplay fair.

##  Gameplay Mechanics

| Mechanic               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Grid Size**          | 20 columns × 12 rows (40px per cell)                                       |
| **Rabbit Movement**    | Grid-based, one cell per move with 120ms cooldown                          |
| **Fox Movement**       | Moves every 550ms toward rabbit using optimal path (greedy AI)             |
| **Carrot Collection**  | Instant score increase + new carrot spawns on a free cell                  |
| **Collision Detection**| Game ends immediately if rabbit and fox share the same cell                |
| **Score Display**      | Real-time counter in the top panel                                         |

##  Technologies Used

- **HTML5** – Structure and canvas element
- **CSS3** – Styling, gradients, shadows, responsive layout
- **JavaScript (ES6)** – Game logic, rendering, event handling, AI movement
- **Canvas API** – All graphics and animations drawn programmatically

No external libraries or frameworks — just vanilla web technologies!

##  Installation & Local Setup

Getting the game running on your local machine is super easy:

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server if you encounter CORS issues — but usually not needed

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rabbit-game.git
   cd rabbit-game
   ```

2. **Open the game**
   - Simply double-click the `index.html` file, OR
   - Use a live server (VS Code Live Server extension, `python -m http.server`, etc.)

3. **Start playing!**  
   The game will load instantly. Use arrow keys or on-screen buttons.

### Folder Structure
```
rabbit-game/
├── index.html          # Complete game (HTML, CSS, JS all in one)
├── README.md           # This file
└── assets/             # (Optional) future images/sounds
```

> **Note:** The game is self-contained in a single HTML file for easy distribution and deployment.

##  Controls

| Action        | Keyboard         | On-Screen Button |
|---------------|------------------|------------------|
| Move Up       |  Arrow Up       |                |
| Move Down     |  Arrow Down     |                |
| Move Left     |  Arrow Left     |                |
| Move Right    |  Arrow Right    |                |
| Restart Game  | Spacebar          | RESTART button   |

##  Customization Ideas

Want to tweak the game? Here are some fun modifications you can make:

- **Change difficulty** – Adjust `MOVE_DELAY_MS` (rabbit speed) and `foxMoveInterval` (fox speed) in the script.
- **Add power-ups** – Introduce temporary shields or speed boosts.
- **Sound effects** – Use Web Audio API to play crunch sounds or game over jingles.
- **High score tracking** – Save best scores using `localStorage`.
- **More enemies** – Add additional foxes or obstacles.
- **Themes** – Create night mode, winter wonderland, or spooky Halloween themes.
- **Leaderboard** – Connect to a simple backend or use IndexedDB.

##  License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this software for personal or commercial purposes, as long as you include the original copyright notice.

##  Contributing

Contributions are welcome! If you have ideas for improvements:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please make sure your code follows the existing style and includes appropriate comments.

##  Acknowledgments

- Inspired by classic arcade games like *Pac-Man* and *Snake*
- Rabbit and fox art drawn with love using Canvas API
- Icons and emojis for visual flair
- Thanks to all open-source contributors who keep web gaming alive!

##  Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)

