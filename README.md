# Simple Painting App

This is a simple painting app built using JavaScript, HTML, and CSS. It allows users to draw on a canvas with various colors and brush sizes, erase their drawings, save their work to localStorage, and reset the canvas.
## Features

    Draw on the canvas with different colors and brush sizes
    Erase mode for correcting mistakes
    Save your work to localStorage
    Reset the canvas to start a new drawing

## Usage

    Open index.html in your preferred web browser.
    Select a color using the color picker.
    Adjust the brush size using the slider.
    Draw on the canvas by clicking and dragging the mouse.
    Switch between paint and erase modes by clicking the "Erase" button.
    Save your work by clicking the "Save" button. The drawing will be saved to your browser's localStorage.
    Clear the canvas by clicking the "Reset" button.

## Code Structure

The javascript.js file contains the main logic of the painting app:

    Initialization of necessary variables and canvas setup.
    Retrieval of the saved image from localStorage (if available) and rendering it on the canvas.
    Event listeners for mouse actions (mousedown, mousemove, mouseup, and mouseleave) to handle painting and erasing on the canvas.
    Event listeners for the "Reset", "Save", and "Erase" buttons.
    Event listeners for color and brush size changes.

## Dependencies

    jQuery: Used to simplify DOM manipulation and event handling.
    jQuery UI Slider: Used to create a slider for adjusting the brush size.

