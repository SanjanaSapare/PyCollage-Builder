# Image Collage Generator

A lightweight Python script that dynamically combines multiple images into a single, cohesive collage using OpenCV and NumPy. The tool automatically resizes and scales images to preserve their original aspect ratios, ensuring a clean final output without distortion.

## Features
* **Dynamic Grid Options:** Supports generating collages with 2, 3, or 4 images.
* **Aspect Ratio Preservation:** Automatically calculates new dimensions to keep images from stretching or squashing.
* **Smart Stacking:** Utilizes NumPy's horizontal (`hstack`) and vertical (`vstack`) stacking to arrange images neatly based on the user's input.
* **Auto-Save:** Displays the final collage in a resizable window and automatically saves it locally as `compound_collage.jpg`.

## Prerequisites
Ensure you have Python installed along with the required libraries. You can install the dependencies using pip:

```bash
pip install opencv-python numpy
