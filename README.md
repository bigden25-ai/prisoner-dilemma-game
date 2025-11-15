# Prisoner's Dilemma Game

A retro pixel-art web-based game that teaches game theory through an interactive implementation of the classic Prisoner's Dilemma. Play against AI opponents with different strategic personalities!

![Retro Game Aesthetic](https://img.shields.io/badge/Style-Retro%20Pixel%20Art-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Play the Game

Simply open `prisoner-dilemma-game.html` in any modern web browser - no installation required!

**Live Demo:** [View on GitHub Pages](https://bigden25-ai.github.io/prisoner-dilemma-game/) (if deployed)

## 🎯 Game Overview

The Prisoner's Dilemma is a classic game theory scenario where two players must decide whether to cooperate or defect. Your choices affect both your score and your opponent's score. The game consists of 10 rounds where you'll face off against AI opponents with different strategic approaches.

## ✨ Features

- **Retro Pixel-Art Design** - Vintage CRT monitor aesthetic with scanlines
- **4 Unique AI Opponents** - Each with distinct strategies and personalities
- **Interactive Character Selection** - Card-based UI with character icons
- **Round History Tracking** - Visual history of all your decisions
- **Score System** - Track your performance across 10 rounds
- **No Dependencies** - Pure HTML, CSS, and JavaScript

## 👥 Meet Your Opponents

### 🟢 Tit-for-Tat
**Trait:** Sneaky  
**Strategy:** Mirrors your last move. Starts with cooperation.  
**Best For:** Learning about reciprocal strategies

### 🔴 The Traitor
**Trait:** Ruthless  
**Strategy:** Never cooperates. Always betrays.  
**Best For:** Testing how to handle constant defection

### 🔵 The Trusting
**Trait:** Naive  
**Strategy:** Always cooperates. Never defects.  
**Best For:** Practicing exploitation strategies

### 🟣 Grudger
**Trait:** Vengeful  
**Strategy:** Cooperates until betrayed once, then never forgives.  
**Best For:** Understanding forgiveness in game theory

## 📊 Scoring System

The payoff matrix determines your points:

| Your Choice | Opponent Choice | Your Points | Opponent Points |
|-------------|----------------|-------------|-----------------|
| Cooperate   | Cooperate      | 3           | 3               |
| Cooperate   | Defect         | 0           | 5               |
| Defect      | Cooperate      | 5           | 0               |
| Defect      | Defect         | 1           | 1               |

**Goal:** Maximize your total score over 10 rounds!

## 🎨 Visual Features

- **Scanlines Effect** - Authentic retro CRT monitor look
- **Pixel Art Characters** - Hand-drawn character sprites
- **Color-Coded History** - Visual representation of round outcomes:
  - 🟢 Green (CC) - Both cooperated
  - 🔴 Red (DD) - Both defected
  - 🟡 Yellow (DC) - You defected, they cooperated
  - 🟠 Orange (CD) - You cooperated, they defected

## 🚀 How to Play

1. **Open the Game** - Double-click `prisoner-dilemma-game.html` or open it in your browser
2. **Choose Your Opponent** - Click on one of the four character cards
3. **Make Your Choice** - Each round, decide to COOPERATE or DEFECT
4. **Watch the Results** - See how your choice affects both scores
5. **Track Your Progress** - Monitor the round history and scores
6. **Win or Learn** - After 10 rounds, see who came out on top!

## 🛠️ Technical Details

- **Single File** - Everything in one HTML file for easy sharing
- **No Build Process** - Works directly in the browser
- **Responsive Design** - Works on desktop and mobile devices
- **Browser Support** - Chrome, Firefox, Safari, Edge (latest versions)

## 📚 Learn More

- **Game Theory** - Learn about strategic decision-making
- **Prisoner's Dilemma** - Understand one of the most famous problems in game theory
- **AI Strategies** - See how different approaches perform

## 📄 Documentation

- [Product Requirements Document (PRD)](PRD.md) - Complete product specifications

## 🎓 Educational Value

This game is perfect for:
- **Students** learning game theory, economics, or psychology
- **Educators** teaching strategic decision-making
- **Anyone** interested in understanding cooperation vs. competition

## 🎮 Game Tips

- **Against Tit-for-Tat:** Cooperation leads to mutual benefit
- **Against The Traitor:** Defect immediately - they'll never cooperate
- **Against The Trusting:** You can exploit them, but consider the ethical implications
- **Against Grudger:** Be careful - one betrayal and they'll never forgive!

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork this project and add your own features:
- Additional AI strategies
- Customizable round counts
- Tournament mode
- Statistics tracking
- And more!

## 🙏 Credits

- **Font:** Press Start 2P (Google Fonts)
- **Design:** Retro pixel-art aesthetic
- **Game Theory:** Based on the classic Prisoner's Dilemma

---

**Enjoy the game and happy strategizing!** 🎯

