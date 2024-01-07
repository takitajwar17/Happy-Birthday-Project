# Project Documentation: Small Happy Birthday Project

## Overview

This project is a web-based animation created using HTML5 Canvas and JavaScript. It generates a visually appealing "Happy Birthday" wish with dynamic elements such as fireworks, floating balloons, and colorful letters. The animation is designed to create a festive and celebratory atmosphere.

### Deployment

The deployed version of this project is available [here](https://takitajwar17.github.io/small-happy-birthday-project/).

## Files

- **index.html**: The main HTML file that structures the document, includes the necessary meta tags, links to external stylesheets and scripts, and sets up the Canvas element.

- **style.css**: The CSS file that provides styling for the HTML elements, including the Canvas positioning, font styles, and other visual properties.

- **app.js**: The JavaScript file that contains the logic for generating the animated elements, such as letters, fireworks, and balloons. It utilizes the HTML5 Canvas API for drawing and animation.

## HTML Structure

The HTML document follows a standard structure, including the DOCTYPE declaration, HTML, head, meta tags, title, and body. The main content is within the body, where the Canvas element is positioned.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags, title, and stylesheets -->
</head>
<body>
    <!-- Canvas element for animation -->
    <canvas id="c"></canvas>

    <!-- JavaScript file for animation logic -->
    <script src="app.js"></script>
</body>
</html>
```

## CSS Styles

The CSS file (`style.css`) is used to style the Canvas and other elements. Notable styles include positioning the Canvas element to cover the entire viewport, styling for the paragraphs, and links.

## JavaScript Logic

The JavaScript file (`app.js`) contains the logic for animating the birthday wish. The key components are:

### Letters

- Each letter is represented as an object with properties such as position, color, and animation phase.
- The animation includes a firework effect, contemplation, and the release of balloons.

### Fireworks

- Fireworks are simulated using lines drawn on the Canvas, creating an animated burst effect.

### Balloons

- Balloons are simulated by inflating and floating upwards, adding a dynamic and festive element to the animation.

## Animation Loop

The `anim()` function serves as the main animation loop, continuously updating and redrawing the Canvas to create the dynamic effects.

## Responsive Design

The project includes a responsive design that adjusts the Canvas size and positioning when the browser window is resized.

## Usage

To view the animation, open the `index.html` file in a modern web browser.

## Author

This project was created by [@takitajwar17](https://github.com/takitajwar17) as a creative and interactive way to send birthday wishes.
