# Interactive Bouncing Balls with Flinging and Text Collision

This project is an HTML5 canvas-based interactive animation featuring bouncing balls that collide with each other and a static text. The balls can be flung around with the mouse, and they respond to gravity, wind, and friction. When the middle mouse button is clicked, the balls "explode" with high velocity, creating a dynamic and engaging visual effect.

## Features

- **Bouncing Balls**: Balls of different sizes and colors bounce around the canvas, colliding with each other.
- **Text Collision**: Balls interact and collide with a static text ("pbritton.dev") rendered at the bottom left of the canvas.
- **Mouse Interaction**: Dragging the balls with the mouse allows users to fling them around the canvas.
- **Responsive Design**: The canvas resizes dynamically to fit the browser window.
- **Physics Simulation**: The balls experience gravity, wind, and friction, creating a realistic motion.

## How to Use

1. **Load the Page**: Open the `index.html` file in a modern web browser.
2. **Interact with Balls**: Click and drag the balls to fling them.
3. **Middle Mouse Button**: Click the middle mouse button to make the balls explode with high velocity.

## Customization

### Text Customization

To change the text displayed on the canvas, update the `text` variable in the JavaScript code:

```javascript
const text = "your-text-here";
```

### Ball Colors

To change the colors of the balls, modify the `colors` array:

```javascript
const colors = ['#color1', '#color2', '#color3', '#color4', '#color5', '#color6'];
```

### Ball Count

To change the number of balls, adjust the `numSmallBalls` variable:

```javascript
const numSmallBalls = your-desired-number-of-balls;
```

### Physics Parameters

- **Gravity**: Change the gravity effect by updating the `ball.vy` increment in the `update` function:

```javascript
ball.vy += your-gravity-value;
```

- **Wind**: Adjust the wind effect by updating the `ball.vx` increment in the `update` function:

```javascript
ball.vx += your-wind-value;
```

- **Friction**: Modify the friction by changing the `friction` variable:

```javascript
const friction = your-friction-value;
```

### Text Font and Style

To customize the font and style of the text, modify the `drawText` function:

```javascript
textCtx.fillStyle = '#your-color';
textCtx.font = 'your-font-size your-font-family';
```

## Technologies Used

- **HTML5 Canvas**: For rendering the animation.
- **JavaScript**: For handling physics, interactions, and animation.

This project demonstrates the use of HTML5 canvas and JavaScript to create an interactive and visually appealing animation. It can be a great starting point for learning about canvas-based animations and physics simulations in web development.
