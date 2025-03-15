# Kid-Friendly Memory Matching Game

![Memory Game Preview](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Age Rating](https://img.shields.io/badge/Age-5%2B-orange)

A colorful, engaging memory card matching game specifically designed for young children. This browser-based game features 20 different themed sets of images that rotate with each new game, keeping the experience fresh and exciting.


## ✨ Features

- **20 Kid-Friendly Themed Sets**:
  - Vehicles (cars, rockets, trains)
  - Animals (lions, elephants, dinosaurs)
  - Dinosaurs (T-Rex, brontosaurus)
  - Space (rockets, planets, astronauts)
  - Sports (soccer, basketball, football)
  - Superheroes (capes, masks, powers)
  - Construction (trucks, tools, signs)
  - Ocean (sharks, dolphins, ships)
  - Robots (robots, tech gadgets)
  - Monsters (friendly monsters, aliens)
  - Plus 10 more exciting themes!

- **Theme Rotation System**:
  - Automatically selects different themes between games
  - Ensures the next game will always have a different theme than the previous two
  - Displays the current theme name above the game board

- **Child-Friendly Design**:
  - Bright, engaging colors and animations
  - Large, easy-to-see emoji images
  - Simple, intuitive interface for young players
  - Animations and visual feedback when matching cards

- **Gameplay Elements**:
  - Score tracking (tries and matches)
  - Victory celebration when all pairs are found
  - Adjustable card viewing time for different difficulty levels

## 🚀 How to Play

1. Click on a card to flip it over and reveal the image
2. Click on another card to find its matching pair
3. If the cards match, they stay face up and turn green
4. If they don't match, they flip back over
5. Find all pairs in as few tries as possible
6. Play again to experience a new theme!

## 💻 Installation & Setup

This is a simple HTML/CSS/JavaScript application with no dependencies. To run the game:

1. Clone this repository:
   ```
   git clone https://github.com/gauravkdesai/memory_game_for_kids.git
   ```

2. Open `memory-matching-game.html` in any modern web browser.

That's it! No build process or installation required.

## 🔧 Customization

### Change the Game Difficulty

You can easily modify the game difficulty by adjusting the following variables in the script:

- `// Change flip-back time (longer = easier)`
  ```javascript
  // Line 261: Change 1200 to a different value (in milliseconds)
  setTimeout(() => {
    flippedCards.forEach(card => {
      card.element.classList.remove('flipped');
    });
    flippedCards = [];
    canFlip = true;
  }, 1200);
  ```

### Add New Themes

Add new emoji sets by expanding the `emojiLibrary` object:

```javascript
// Add your new theme
"YourTheme": ['emoji1', 'emoji2', 'emoji3', 'emoji4', 'emoji5', 'emoji6', 'emoji7', 'emoji8'],
```

## 👨‍💻 Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- No external dependencies or libraries
- Mobile-friendly responsive design
- Animated with CSS transitions and keyframes
- Theme rotation logic to ensure variety

## 📋 Future Enhancements

- [ ] Sound effects for card flips and matches
- [ ] Difficulty levels (easy, medium, hard)
- [ ] High score tracking
- [ ] Different grid sizes (4x4, 6x6)
- [ ] Custom themes upload option
- [ ] Timer mode

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Designed for young children to enjoy and develop cognitive skills
- Inspired by classic memory/concentration card games
- Emojis provided by standard Unicode character set
- This game was created with assistance from Claude, an AI assistant by Anthropic. Content generated with Claude can be used for personal or commercial purposes, including publishing, with attribution to Anthropic appreciated but not required. See [Anthropic's Terms of Use](https://www.anthropic.com/terms) for more details.


---

Made with ❤️ for young learners
