# Cannon Game

## Overview

The Cannon Game is an interactive web-based game where the player controls a cannon to shoot at falling balloons. The goal is to hit as many balloons as possible while avoiding misses that reduce the player's lives. The game ends when the player's lives reach zero. This project demonstrates HTML5 canvas animations, sound integration, responsive design, and interactive gameplay mechanics using JavaScript.

---

## Features

- **Responsive Canvas**: The game dynamically resizes the canvas to fit the browser window.
- **Cannon Control**: The player can move the cannon left or right and adjust the turret angle.
- **Projectile Mechanics**: A cannonball is fired at the current turret angle and checks for collisions with balloons.
- **Balloon Dynamics**: Balloons spawn at random positions and fall at a set speed.
- **Scoring System**: Points are awarded for successfully hitting balloons, and lives are deducted for misses.
- **Game Over Mechanic**: The game ends when the player runs out of lives.
- **Sound Effects**: Includes sounds for firing and explosions.
- **Interactive UI**: A control panel to adjust the cannon speed, and a display of remaining lives and score.

---

## Technologies Used

1. **HTML5**: For structuring the game elements.
2. **CSS3**: For styling and positioning the game canvas and controls.
3. **JavaScript**: For implementing game logic, animations, and user interactions.

---

## Game Controls

- **Arrow Left**: Move the cannon to the left.
- **Arrow Right**: Move the cannon to the right.
- **Arrow Up**: Raise the cannon turret angle (maximum -35°).
- **Arrow Down**: Lower the cannon turret angle (maximum 20°).
- **Spacebar**: Fire the cannonball.
- **Speed Slider**: Adjust the cannon's movement speed.

---

## File Structure

```
|-- index.html       # Main HTML file containing the game structure
|-- styles.css       # Embedded CSS for styling the game (within <style> tag)
|-- script.js        # Embedded JavaScript for game logic (within <script> tag)
|-- assets/          # Folder for game assets (images and audio files)
    |-- Background.jpg
    |-- Carriage.png
    |-- Turret.png
    |-- Wheel.png
    |-- FuGo.png
    |-- explosion.gif
    |-- shot.m4a
    |-- explosion.m4a
```

---

## Installation and Setup

1. Clone or download the repository.
2. Place the `index.html` file and the `assets` folder in the same directory.
3. Open the `index.html` file in any modern web browser.

---

## How to Play

1. Use the arrow keys to control the cannon's movement and turret angle.
2. Fire cannonballs at the falling balloons by pressing the Spacebar.
3. Adjust the cannon speed using the speed slider in the control panel.
4. Avoid missing balloons as each miss reduces your lives.
5. The game ends when all lives are lost.

---

## Customization

- **Assets**: Replace the images and audio files in the `assets` folder to customize the game visuals and sounds.
- **Balloon Speed**: Modify the `balloon.speed` value in the JavaScript code to change the balloon falling speed.
- **Lives and Score**: Adjust the initial `lives` and `score` values in the script for different game difficulty.
- **Explosion Display**: Customize the explosion duration in the `handleMiss` function by changing the `setTimeout` value.

---

## Known Issues

1. The game may become unresponsive if assets are missing or improperly linked.

---

## Author

- **Name**: Chowdhury Yasir


