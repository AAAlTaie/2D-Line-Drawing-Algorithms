# 2D-Line-Drawing-Algorithms
This project is to showcase the creation of  primitive types in 2D space, focusing on points and lines utilizing: Bresenham's Line Algorithm,  Midpoint Line Algorithm and  Parametric Line Algorithm.

# Overview

Welcome to the 2D Line Drawing Algorithms repository! This project implements fundamental line-drawing algorithms in a 2D space using C++. These algorithms are essential for understanding basic computer graphics and rendering techniques.

# Objective

The main goal of this project is to create primitive types in 2D space, focusing on points and line-drawing algorithms:

1. Bresenham's Line Algorithm.
2. Midpoint Line Algorithm.
3. Parametric Line Algorithm.

# Key Features to Achieve full implementation:

- Back Buffer Management: Set up a back buffer and clear it to a specified color, ensuring a fresh drawing surface for each render cycle.
  
- Pixel Drawing Functionality: Implement a function to draw a pixel at a given position with a specified color, serving as the foundation for drawing lines.

- Line Drawing Algorithms: Develop and encapsulate the following line algorithms into function calls for reusability and ease of debugging:
  - Bresenham's Line Algorithm: Efficiently draw lines with a positive slope, starting from (x0, y100) to (x499, y400).
  - Midpoint Line Algorithm: Calculate and draw lines by determining the midpoint between start and end points.
  - Parametric Line Algorithm: Use parameterization to compute and render lines between given start and end points.

- Positive Slope Line Handling**: Ensure that all implemented algorithms can handle lines with positive slopes, where both the x and y coordinates increase from the start to the end point.

- Modular Code Structure**: Encapsulate each line algorithm in its own function to allow multiple calls, facilitate debugging, and aid in collaborative development.

This project not only demonstrate my understanding of the basics of line drawing but also lays the groundwork for more advanced graphics programming.
