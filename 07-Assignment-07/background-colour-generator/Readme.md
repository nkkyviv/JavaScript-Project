# Random RGB Color Generator

A simple web project that dynamically generates random RGB colors and updates the background color of the page. This project is great for learning **JavaScript DOM manipulation**, **CSS styling**, and **random number generation**.

---

## Demo

When you click the **"Generate Color"** button:

- The background color of the page changes to a random RGB color.
- The RGB color code is displayed on the page in real-time.

---

## Features

- Generates random RGB colors using JavaScript.
- Updates both the background color and the displayed RGB code.
- Smooth transitions for background color changes.
- Responsive and visually appealing UI.

---

## How It Works

1. **HTML Structure**  
   - A container with:
     - A heading (`Current Background Color`)
     - A display box for the RGB code
     - A button to generate a new color

2. **CSS Styling**  
   - Flexbox layout to center content.
   - Smooth background-color transitions.
   - Styled button with hover effects.
   - Shadowed container for better aesthetics.

3. **JavaScript Functionality**  
   - Select DOM elements (`body`, `colorDisplay`, `generateBtn`).
   - Function `getRandomValue()` generates a random number between `0-255`.
   - Function `generateColor()`:
     - Generates random `red`, `green`, `blue` values.
     - Constructs a string `rgb(red, green, blue)`.
     - Updates the body's background color.
     - Updates the color code display on the page.
   - Event listener on the button to trigger `generateColor()` on click.

---

## Learning Outcomes

By building this project, you will learn:

How to select and manipulate DOM elements.

How to use event listeners to respond to user actions.

How to generate random numbers in JavaScript.

How to use template literals for dynamic strings.

How to style elements using CSS, including hover effects and transitions.
