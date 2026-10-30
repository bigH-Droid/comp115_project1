# New York Skyline with Python Turtle

## Description

This project creates a nighttime drawing of the New York City skyline inspired by the video game **Deadlock**, using Python's `turtle` graphics library.

The project demonstrates basic concepts in Python graphics, including:

- Drawing shapes using rectangles and lines
- Using functions to organize and reuse code
- Using `for` loops to draw buildings, windows, and other details
- Using conditional statements (`if`) to control window lighting
- Using randomization to create different lighting patterns
- Using coordinates to position objects on the screen

## Code Overview

The project is structured around a few reusable functions:

- `rectangle(x, y, width, height, color)` - Draws a filled rectangle, used for buildings, windows, doors, and other details.
- `line(x1, y1, x2, y2, color, size)` - Draws lines with different colours and thicknesses.
- `windows(x, y, width, height, step_x, step_y)` - Creates windows inside buildings with different lighting colours.
- `rooftop(x, y, width)` - Draws the rooftops of the surrounding skyscrapers.

The `random` module is used to create different window lighting patterns. A fixed random seed is used so the lighting stays consistent each time the program runs.

The screenshot of the drawing can be found on the sidebar, in the main repository.

## How to Run

1. Download or clone the raw code.
2. Open the project file in VS Code or another Python reader.
3. Make sure Python is installed.
4. Run the program:
5. A Turtle graphics window will open showing the New York skyline.
6. Close the window to end the program.

## License

This project is open-source and free to use for educational purposes.
