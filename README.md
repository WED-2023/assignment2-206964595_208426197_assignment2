# Space Invaders Game
## creators
Yuval Ellins - 206964595 

Idan Duhaviv - 208426197

Website -  https://wed-2023.github.io/assignment2-206964595_208426197_assignment2/




## Overview

This project is a web-based Space Invaders game created using HTML, CSS, and JS. The game features classic Space Invaders gameplay with modern enhancements including user accounts, customizable controls, different ship styles, and various gameplay features.

## Features

### User Management
- **Registration System**: Create new user accounts with validation
- **Login System**: Secure authentication for returning players
- **Score History**: Track and display personal best scores

### Game Customization
- **Control Customization**: Rebind movement and firing keys to your preference
- **Ship Customization**: Choose between different colored player ships (Blue, Green, Red, Gold)
- **Game Duration**: Set your preferred game time (minimum 2 minutes)

### Gameplay Features
- **Multiple Lives**: Players have three lives per game
- **Score System**: Different points for different enemy rows (5-20 points)
- **Difficulty Progression**: Enemies and their shots accelerate over time
- **Victory Conditions**: Win by eliminating all enemies or reaching a high score before time expires

## Technical Implementation

### Project Structure
- `index.html`: Main game HTML structure
- `style.css`: Game styling and animations
- JavaScript: Contained in the HTML file for simplicity

### Game Architecture
The game is built using a component-based approach with the following key elements:

1. **Screen Management**: Multiple game screens (Welcome, Login, Register, Settings, Game, Score) with transitions
2. **User Authentication**: Simple client-side user management system
3. **Game Loop**: Controlled via interval timers for enemies, shots, and game state
4. **Collision Detection**: Custom collision detection between player/enemies and shots
5. **Dynamic Difficulty**: Speed adjustments based on time elapsed
6. **Score Tracking**: Persistent score history for logged-in users

### Key Technical Challenges
- **Collision Detection**: Implementing precise collision detection between shots and ships
- **Enemy Movement Patterns**: Creating responsive enemy movement that changes direction at screen boundaries
- **Custom Controls**: Supporting rebindable keys without conflicts
- **Game State Management**: Handling transitions between screens and preserving player data
- **Responsive Design**: Making the game playable on different viewport sizes

## How to Run

1. Clone this repository
2. Open `index.html` in a modern web browser
3. Register a new account or use the test account:
   - Username: `p`
   - Password: `testuser`


## Controls

Default controls (can be customized in Settings):
- **Move Left**: Left Arrow
- **Move Right**: Right Arrow
- **Move Up**: Up Arrow
- **Move Down**: Down Arrow
- **Fire**: Space


### Browser Compatibility
- Chrome only

### Performance Considerations
- Enemy and shot movements are optimized using requestAnimationFrame
- Object creation/destruction minimized during gameplay
- Audio preloading to prevent playback delays

## Credits
- Created by Yuval Ellins and Idan Duhaviv
- Developed as an educational project for BGU SISE
- Audio effects and graphics are open source and used for educational purposes

## License
This project is available for educational purposes. Please credit the authors if you use or modify the code.

---

© 2025 BGU SISE Students. All rights reserved.
