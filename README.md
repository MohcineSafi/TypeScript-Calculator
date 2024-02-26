# Calculator Web Application

The Calculator web application provides users with a simple yet powerful tool to perform basic arithmetic calculations. Users can input mathematical expressions using numbers, operators, and parentheses, and the application will evaluate and display the result in real-time.

## Features

- **Arithmetic Operations**: Users can perform addition, subtraction, multiplication, and division operations using the corresponding buttons.
- **Parentheses Support**: The application supports the use of parentheses to define the order of operations.
- **Error Handling**: In case of invalid input or calculation errors, the application displays an error message to alert the user.
- **Clearing and Deleting**: Users can clear the input or delete the last character using the "C" and backspace buttons, respectively.
- **Responsive Design**: The application is designed to work well on various screen sizes and devices.

## Files

- **index.html**: Contains the HTML structure of the calculator interface, including buttons for numbers, operators, and controls.
- **styles.css**: CSS file that provides styling for the calculator interface.
- **Calculator.ts**: TypeScript file containing the logic for performing arithmetic calculations, handling input, and error checking.
- **app.ts**: TypeScript file responsible for initializing event listeners and connecting the user interface with the calculator logic.
- **elements.ts**: TypeScript file that defines constants for DOM elements used in the application.
- **functions.ts**: TypeScript file containing helper functions for displaying results and handling button clicks.

## Dependencies

- **Font Awesome**: The application uses Font Awesome icons to enhance the visual appearance of buttons and controls.
- **Google Fonts (Lato)**: The Lato font family from Google Fonts is used for text elements in the calculator interface.

## Usage

1. Open the `index.html` file in a web browser.
2. Use the number buttons (0-9) to input numerical values.
3. Use the operator buttons (+, -, *, /, %) to perform arithmetic operations.
4. Use parentheses to group expressions and define the order of operations.
5. Click the "C" button to clear the input or the backspace button to delete the last character.
6. Click the "=" button to calculate the result.
7. View the calculated result in real-time in the result section.
