# Vertical Air Hockey Game

Welcome to the Vertical Air Hockey Game! This web-based game allows you to play a fun and engaging air hockey game against an AI opponent. 

## Features

- **Smooth Paddle and Puck Movement**: Enjoy realistic paddle and puck dynamics.
- **AI Opponent**: Challenge yourself against an AI with different states and behaviors.
- **Responsive Design**: The game is playable on both desktop and mobile devices.
- **Particle Effects**: Enjoy visual explosions when goals are scored.
- **Score Tracking**: Keep track of scores with a clear and easy-to-read scoreboard.
- **Countdown Timer**: A countdown timer to get ready before each round starts.

## Getting Started

### Prerequisites

To run this game, you only need a web browser that supports HTML5 and JavaScript.

### Running the Game

1. **Download the Project**: Clone or download the project files to your local machine.
2. **Open the Game**: Open the `index.html` file in your preferred web browser.
3. **Start Playing**: Use your mouse or touch screen to control the paddle and start playing against the AI.

### Controls

- **Mouse**: Move your paddle by moving the mouse.
- **Touch**: Move your paddle by touching and dragging on the screen.

## Code Overview

The project is built using HTML5 Canvas and JavaScript. Below is a brief overview of the key parts of the code:

### HTML

The `index.html` file sets up the structure of the game, including the canvas and the scoreboard.

### CSS

The CSS within the `index.html` file styles the game elements, including the canvas and the scoreboard, ensuring a visually appealing layout.

### JavaScript

The JavaScript code controls the game logic, including:

- **Paddle and Puck Movement**: Functions for drawing and moving the paddles and puck.
- **AI Logic**: Functions that control the AI paddle's behavior.
- **Collision Detection**: Functions that detect collisions between the puck and the paddles, and the puck and the goals.
- **Explosion Effects**: Functions for creating and drawing particle effects when a goal is scored.
- **Score Update**: Functions for updating the scoreboard.
- **Animation Loop**: The main game loop that uses `requestAnimationFrame` for smooth animations.

### Main Functions

- `drawTable()`: Draws the table layout.
- `drawPaddle()`: Draws the paddles.
- `drawPuck()`: Draws the puck.
- `movePaddle()`: Handles paddle movement.
- `handleMouseMove()`, `handleTouchMove()`: Handle input events.
- `isPuckStuck()`: Checks if the puck is stuck in corners.
- `moveAIPaddle()`: Moves the AI paddle.
- `collisionDetection()`: Detects collisions and handles score updates.
- `createExplosion()`, `drawExplosion()`: Manages particle effects.
- `drawCountdown()`: Draws the countdown timer.
- `draw()`: Main drawing and updating loop.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is open-source and available under the MIT License. 