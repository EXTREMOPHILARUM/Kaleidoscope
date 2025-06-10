# Interactive Kaleidoscope

This is a creative coding project built with p5.js that generates beautiful, symmetrical, and animated patterns. Users can draw freely, generate complex patterns from mathematical formulas, and record and replay their creations.

## Features

* **Symmetrical Drawing:** Draw patterns with a configurable number of symmetrical segments.
* **Continuous Rotation:** The canvas gently rotates, creating a dynamic and mesmerizing effect.
* **Animated Formulas:** Automatically generate beautiful, animated patterns from classic mathematical formulas, including:
    * Lissajous Curve
    * Maurer Rose
    * Spirograph
    * Supershape
    * Butterfly Curve
* **Evolving Colors:** Both freehand drawings and formulas are rendered with a continuously shifting rainbow hue.
* **Record & Replay:** Record your drawing sessions—including a mix of freehand strokes and formula animations—and play them back in a continuous "boomerang" loop.

## How to Use

1.  **Select a Mode:** Use the "Formula" dropdown to switch between **Freehand Drawing** and various mathematical formulas.
2.  **Freehand Drawing:**
    * Click and drag on the canvas to draw.
    * Use the **Symmetry** slider to change the number of reflections.
    * Click **Record** to start capturing your drawing. Click **Stop** when finished.
    * Click **Replay** to watch your recording in a boomerang loop.
3.  **Formula Mode:**
    * Select a formula from the dropdown.
    * Click the **Draw Formula** button to generate the pattern. The drawing will be animated.
    * You can also record the formula animations by clicking **Record** before drawing.
4.  **Clear:** Use the **Clear** button at any time to reset the canvas.

## Technologies Used

* **HTML/CSS:** For the application structure and styling.
* **p5.js:** A JavaScript library for creative coding that handles all drawing and animation logic.
