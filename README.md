# Calculator Web Application

This project is a simple calculator web application. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- Percentage calculation.
- Clear entry (CE) and clear all (C) functionality.
- Responsive design that adjusts to different screen sizes.

## Technologies Used

- HTML
- CSS

## HTML Structure

The HTML structure consists of a `container` div that contains a `calc` div. Inside the `calc` div, there is a form that contains two main divs: `display` and `keypad`. The `display` div is used to display the input and result of the calculation. The `keypad` div contains multiple rows of input buttons representing the digits (0-9), arithmetic operators (+, -, *, /), and special functions (% for percentage, CE for clear entry, C for clear all).

## CSS Styling

The CSS styling includes a background image for the body and specific styles for the calculator such as dimensions, colors, font sizes, etc. The calculator has a semi-transparent background color which allows the background image to be partially visible.

## How to Use

To use the calculator, simply click on the buttons on the keypad. The clicked button's value will be displayed in the display area. If an arithmetic operator button is clicked, it will perform that operation on the current input and the result will be displayed.

## Note

Please ensure that the path to the background image in the CSS file is correct. If the image is not loading, check if the image file exists in the specified path.

## Future Improvements

This is a basic version of a calculator web application. Future improvements can include advanced mathematical functions, memory functions, error handling for invalid inputs or calculations, etc.