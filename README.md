# Ball in a Box

This simple web application creates an interactive "Ball in a Box" simulation using HTML, CSS, and JavaScript. The ball responds to window movement, simulating physics-based motion within the browser window.

## Features

- A red ball that moves within the confines of the browser window
- Physics simulation including gravity, friction, and restitution
- Responsive to window movement, affecting the ball's velocity
- Collision detection with window boundaries

## How it Works

The application uses:

- HTML to structure the page
- CSS to style the ball and set up the visual environment
- JavaScript to handle the physics simulation and animation

The ball's movement is influenced by:

- Gravity: Constant downward force
- Friction: Slows the ball's movement over time
- Restitution: Determines the ball's bounciness when hitting window edges
- Window Movement: Changes in the window's position affect the ball's velocity

## Usage

1. Clone this repository
2. Open `index.html` in a web browser
3. Move your browser window to see the ball react to the movement

## Customization

You can adjust the following variables in the JavaScript to change the ball's behavior:

- `friction`: Controls how quickly the ball slows down
- `gravity`: Controls the strength of downward force
- `restitution`: Controls the ball's bounciness 
- `xSensitivity` and `ySensitivity`: Control how much window movement affects the ball

