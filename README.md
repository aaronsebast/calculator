# Simple Calculator

This is a simple web-based calculator built using **HTML**, **CSS**, and **JavaScript**. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## Features

- **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
- **User-Friendly Interface**: Easy-to-use buttons for numbers, operators, and clearing the screen.
- **Real-Time Display**: Displays the input and results on the screen.
- **Responsive Design**: Adjusts well to different screen sizes.

---

## How It Works

1. **Numbers and Operators**: Click the number and operator buttons to build a mathematical expression.
2. **Equal (`=`)**: Press the `=` button to evaluate the expression.
3. **Clear (`C`)**: Press the `C` button to reset the calculator and start fresh.

---

## File Structure

- **HTML (Structure)**: Defines the layout of the calculator interface.
- **CSS (Style)**: Adds styling to make the calculator visually appealing.
- **JavaScript (Logic)**: Provides functionality for the calculator buttons and manages the operations.

---

## Code Overview

### HTML

- The calculator interface is built using a grid layout.
- Buttons are categorized into numbers, operators, and actions.

### CSS

- Styles include a modern grid-based layout, rounded buttons, and clear colors for easy usability.

### JavaScript

The logic is implemented through the following functions:
- **`updateDisplay(value)`**: Updates the display screen.
- **`clearDisplay()`**: Clears the display and resets the calculator.
- **`addToDisplay(value)`**: Adds numbers or decimal points to the display.
- **`addOperator(operator)`**: Adds operators (e.g., `+`, `-`, `/`) to the display, with checks to prevent errors.
- **`calculate()`**: Evaluates the mathematical expression and displays the result.

---

## Example

1. Press `8`, `+`, `5`, and `=` → The result displayed is `13`.
2. Press `C` → The display resets to `0`.

---

## Customization

You can enhance this calculator by:
- Adding more operators (e.g., square root, percentage).
- Improving error handling for invalid inputs.
- Styling it further with CSS animations.

---

