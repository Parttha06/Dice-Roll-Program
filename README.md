# 🎲 Dice Roll Simulator

A fun and interactive Dice Roll Program built with HTML, CSS, and JavaScript. Roll a single die or multiple dice at once - perfect for games, decision-making, or just for fun!

## ✨ Features

- 🎲 **Single Die Roll** - Roll a standard 6-sided die
- 🎲🎲 **Multiple Dice** - Roll multiple dice simultaneously
- 🎨 **Visual Display** - See your dice results clearly
- ⚡ **Quick & Responsive** - Instant results with smooth interactions
- 📱 **Mobile Friendly** - Works on all devices
- 
## 🛠️ Built With

- **HTML5** - Structure and layout
- **CSS3** - Styling and visual effects
- **JavaScript** - Dice rolling logic and randomization

## 📂 Project Structure

```
dice-roll-simulator/
│
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # Dice rolling logic
└── README.md           # Project documentation
```

## 🎮 How to Use

1. **Single Die Mode**:
   - Click "Roll Die" button
   - Get a random number between 1-6
   - Roll again as many times as you want!

2. **Multiple Dice Mode**:
   - Select number of dice (2, 3, 4, etc.)
   - Click "Roll Dice" button
   - See all dice results at once
   - Total sum is calculated automatically

## 💻 How It Works

### Single Die Roll Logic
```javascript
function rollDie() {
    return Math.floor(Math.random() * 6) + 1;
}

// Generate random number between 1-6
const result = rollDie();
```

### Multiple Dice Roll Logic
```javascript
function rollMultipleDice(numberOfDice) {
    let results = [];
    for (let i = 0; i < numberOfDice; i++) {
        results.push(Math.floor(Math.random() * 6) + 1);
    }
    return results;
}

// Roll 3 dice example
const diceResults = rollMultipleDice(3);
// Example output: [4, 2, 6]
```

## 🎲 Dice Probability

Each die face has an equal probability:
- Probability of any number (1-6): **1/6 or ~16.67%**
- Total possible outcomes: **6**
- Expected average: **3.5**

### Multiple Dice Statistics
| Dice Count | Minimum | Maximum | Average |
|------------|---------|---------|---------|
| 1          | 1       | 6       | 3.5     |
| 2          | 2       | 12      | 7       |
| 3          | 3       | 18      | 10.5    |
| 4          | 4       | 24      | 14      |

## 🎯 Getting Started

### Prerequisites
- A web browser (Chrome, Firefox, Safari, etc.)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/dice-roll-simulator.git
```

2. Navigate to the project directory
```bash
cd dice-roll-simulator
```

3. Open `index.html` in your browser
```bash
# On Windows
start index.html

# On Mac
open index.html

# On Linux
xdg-open index.html
```

Or simply drag and drop the `index.html` file into your browser!

## 🎨 Customization

Enhance your dice roller:
- **Dice visuals** - Display actual dice faces (⚀ ⚁ ⚂ ⚃ ⚄ ⚅) using Unicode or images
- **Animations** - Add rolling animation effects
- **Sound effects** - Play dice rolling sounds
- **Color themes** - Change color schemes
- **Custom dice** - Add d4, d8, d10, d12, d20 (for RPG games)
- **Background** - Add themed backgrounds

## 📚 What I Learned

This project helped me understand:
- ✅ Random number generation with `Math.random()`
- ✅ Array manipulation and iteration
- ✅ Working with loops (for multiple dice)
- ✅ DOM manipulation and dynamic content
- ✅ Event handling and user interactions
- ✅ Probability and statistics concepts

## 🔮 Future Enhancements

Ideas to level up your dice roller:
- 🎬 **Roll Animations** - Spinning/tumbling dice effects
- 📊 **Statistics Tracker** - Count frequency of each number
- 📜 **Roll History** - Keep track of previous rolls
- 🎲 **Custom Dice Types** - d4, d8, d10, d12, d20 for RPG games
- 🎯 **Target Number** - Set a goal and track if you hit it
- 🎮 **Game Modes** - Yahtzee, Craps, Farkle rules
- 💾 **Save Results** - Local storage for roll history
- 🏆 **Achievements** - Unlock badges for rare rolls (all 6's, etc.)
- 🎨 **3D Dice** - WebGL 3D dice with physics
- 🔊 **Sound Effects** - Realistic dice rolling sounds
- 📱 **Shake to Roll** - Use device motion sensors

## 🎮 Use Cases

Perfect for:
- 🎲 Board game sessions
- 🎯 Decision making ("Let the dice decide!")
- 🎪 Party games
- 🧙 RPG/D&D games (can add d20, d12, etc.)
- 🎰 Probability demonstrations
- 📚 Teaching randomness and statistics
- 🎮 Game development testing

## 🎲 Fun Dice Facts

- The opposite sides of a standard die always add up to **7**
- Dice have been used for over **5,000 years**
- The plural of "die" is "dice"
- Casino dice are called "perfect" or "precision" dice
- A d20 (20-sided die) is most famous from Dungeons & Dragons

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Partha Biswas**

- GitHub: [@Parttha06](https://github.com/Parttha06)
- LinkedIn: [Partha Biswas](www.linkedin.com/in/partha-biswass)

## 🙏 Acknowledgments

- Inspired by classic dice games and randomness
- Built as part of my JavaScript learning journey
- Great for understanding random number generation

## ⭐ Show Your Support

Give a ⭐️ if you rolled a 6! (Or any number, really 😄)

---

<div align="center">
Made with ❤️ and a sprinkle of randomness by Partha Biswas

🎲 May the odds be ever in your favor! 🎲
</div>
