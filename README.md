# Basic-Calculator
Understood — no usage section, and more content.
Here is an expanded README.md with richer explanation, details, and description:

📟 Calculator Web Application

This project is a modern, animated calculator built using HTML, CSS, and JavaScript.
It provides an intuitive interface for performing basic arithmetic calculations while showcasing smooth UI transitions and clean design principles.

✨ Overview

The calculator features a minimalistic layout with a focus on usability and aesthetics.
The interface includes a numeric keypad, essential arithmetic operators, a decimal point, an equals button, and a dedicated clear function.

This project demonstrates:

Interactive DOM manipulation

Custom CSS animations

Grid-based UI layout

Real-time expression evaluation

Basic error handling

🎨 Design & UI Details
Animations

The main calculator container uses a slide-in animation, creating a smooth entrance when the page loads.

All buttons include a fade-in animation to enhance visual appeal.

Hover effects provide feedback by scaling buttons slightly and changing background color.

Layout

The layout is built using CSS Grid, providing a clean 4×4 grid for buttons.

The display area is positioned above the grid and aligned to the right, resembling modern digital calculators.

Colors were chosen to maintain clarity:

Light gray backgrounds for number buttons

Yellow accents for operators

Red highlight for the clear button

🧠 JavaScript Functionality

The calculator logic is intentionally simple and easy to read:

press(value)

Appends a number or operator to the current display string.

clearDisplay()

Fully resets the display content.

calculate()

Evaluates the current expression using JavaScript’s evaluation engine.

If the expression is valid, the result replaces the input.

If invalid, the display shows "Error".

This function also prevents the app from crashing due to malformed expressions.
