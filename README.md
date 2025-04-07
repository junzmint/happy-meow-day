# 🎉 Cat Birthday Adventure 🐱

An interactive HTML/CSS/JavaScript birthday card with a playful cat-themed mini-game where players collect fish, avoid bombs, and unlock a festive greeting card.

[![Play Now](https://img.shields.io/badge/🐱_Play_Now-Live_Demo-2ecc71?style=for-the-badge&logo=github)](https://junzmint.github.io/happy-meow-day/)

## ✨ Features

### Gameplay
- 🕹️ **Mini-Game**: Navigate a cat character using arrow keys or on-screen controls
- 🐟 **Collectibles**: Gather fish for +50 points each
- 💣 **Obstacles**: Avoid bombs that halve your score and cost lives
- ❤️ **Lives System**: 5 lives before game over
- ⏱️ **Time Challenge**: 60-second countdown timer

### Visuals
- 🎨 **Animations**: 
  - Floating fish and rotating bombs
  - Cat reaction sprites (happy/sad faces)
  - Confetti victory effects
- 🌳 **Obstacles**: Tree walls that block movement

### Experience
- 📱 **Responsive Design**: Works on desktop and mobile
- 🎁 **Unlockable**: Game completion reveals special birthday card
- 📛 **Personalized**: Player name input at start

## 🚀 How to Play

1. Enter your name when prompted
2. Read the game rules
3. Control the cat using:
   - **Desktop**: Arrow keys (↑ ↓ ← →)
   - **Mobile**: On-screen directional buttons
4. Collect fish while avoiding bombs
5. Complete before time runs out to unlock the birthday card!

## 🛠️ Development

### Setup
```bash
git clone https://github.com/junzmint/happy-meow-day.git
cd happy-meow-day
```

### Customization
- Messages: Edit text in birthday-card.html
- Appearance: Modify colors in CSS variables
- Gameplay: Adjust settings in script:
```javascript
const GRID_SIZE_X = 13;
const GRID_SIZE_Y = 10;
let timeLeft = 60;
const MAX_LIVES = 5;
```

## 🧰 Technologies

### Frontend
- HTML5
- CSS3 (Animations/Flexbox/Grid)
- Vanilla JavaScript

## 🤝 Contribution

### Suggestions and improvements welcome! Potential enhancements:
- 🔊 Add sound effects/music
- 🏆 High score system (Use a JSON or TXT file)
- 🎚️ Difficulty levels (Change time, obstacles, bomb, ...)
- ✨ New power-ups/collectibles (Plus more time, jump through the tree, eat all the fish nearby, ...)

### How to contribute ?
1. Fork the repository
2. Create your feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

## 🔮 Note
This project was initially generated with assistance from DeepSeek AI for discovering the power of this new AI model, then customized and enhanced! I did nothing, just prompt and prompt for the new features. Of course the code look like a mess but you can arrange it as you want, I just want to find out how strong this AI model is in the term of UIUX design.
