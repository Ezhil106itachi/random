# Random Ball Program

## Overview

The Random Ball program is a simple web application that generates a colorful ball at a random position within the browser window. Each time the page is loaded, a new ball is created with a random size and color, making for a visually engaging experience.

## Features

- **Randomized Ball Creation**: Each ball has a unique color and size, appearing at a random position on the screen.
- **Responsive Design**: The ball adjusts its position based on the viewport size, ensuring it fits within the visible area.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. **Open the HTML File**: Save the code as an `.html` file (e.g., `random_ball.html`) and open it in a web browser.
2. **View the Random Ball**: Refresh the page to generate a new ball with a different size, color, and position.

## Code Explanation

- **CSS Styles**: Basic styling is applied to the body and the ball class to ensure the ball is circular and positioned absolutely on the screen.
- **Random Color Generation**: The `getRandomColor()` function generates a random hex color code.
- **Ball Creation Logic**:
  - The `createRandomBall()` function calculates the viewport dimensions to ensure the ball fits within the window.
  - A new `<div>` element is created for the ball, with a random size, position, and color.
  - The ball is then appended to the body of the document.

## Customization

You can customize the following aspects of the program:

- **Ball Size Range**: Modify the range in `Math.floor(Math.random() * 50) + 50` to change the minimum and maximum size of the balls.
- **Background Color**: Change the `background-color` in the body style to set a different background for the page.
- **Multiple Balls**: To create multiple balls, you can call `createRandomBall()` in a loop.

## Conclusion

This Random Ball program serves as a fun introduction to JavaScript and DOM manipulation. Feel free to experiment with the code to add more features or enhance the visual effects! Enjoy creating random balls!
