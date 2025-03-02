# Rico's Multiplayer Circle Game

A fun, interactive browser-based game where players click on randomly moving circles to score points.

## Description

Rico's Multiplayer Circle Game is a web-based reaction game where colorful circles appear on screen, move around, and players must click them to earn points. The game features multiple modes, difficulty settings, and a persistent scoreboard.

## Game Features

### Game Modes
- **Timed Mode**: Score as many points as possible within a time limit (15, 30, or 60 seconds)
- **Target Mode**: Race to reach a target score (50, 100, or 200 points) as quickly as possible
- **Survival Mode**: Circles disappear over time, and each hit adds more time to your countdown

### Difficulty Settings
- 5 difficulty levels from Very Easy to Very Hard
- Higher difficulties feature:
  - Smaller circles
  - Faster movement
  - More frequent spawns
  - Higher scoring potential

### Gameplay Mechanics
- Circles have different sizes, colors, and point values
- Smaller circles are worth more points but are harder to hit
- Circles bounce off walls and move at different speeds
- Missed clicks reduce your accuracy percentage
- In Survival mode, circles fade out over time and cost you time if missed

### Scoreboard System
- Persistent leaderboard saved in browser local storage
- Filter scores by game mode
- Highlights current player's scores
- Shows rank, player name, score, game mode, accuracy, and date

### Admin Features
- Password-protected admin panel
- Option to reset all scores

## How to Play

1. Enter your player name and click "Set Player"
2. Select your game mode, time limit or target score, and difficulty level
3. Click "Start Game" to begin
4. Click on the circles as they appear to earn points
5. Game ends when time runs out (Timed mode), you reach the target score (Target mode), or your countdown hits zero (Survival mode)

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Game state and scores persisted using browser localStorage
- Responsive design that adapts to different screen sizes
- No external dependencies required

## Setup and Installation

1. Download all files to your local machine
2. Open the HTML file in any modern web browser
3. No server or installation required

## Browser Compatibility

The game works on all modern browsers with JavaScript enabled, including:
- Chrome
- Firefox
- Safari
- Edge

## Future Enhancements

Potential future improvements could include:
- Multiplayer functionality via WebSockets
- Power-ups and special abilities
- Additional game modes
- Sound effects and music
- Mobile-optimized touch controls
