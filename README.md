# SimpleCalculator
A simple, responsive calculator built using **HTML**, **CSS**, and **JavaScript**. The calculator can perform basic arithmetic operations like addition, subtraction, multiplication, and division.

Features
- **Clear Display**: "AC" button clears the entire input.
- **Delete Functionality**: "DE" button removes the last character from the input.
- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Decimal Support**: Allows users to input and calculate decimal numbers.
- **Error Handling**: Prevents invalid inputs using safe evaluation of expressions with enhanced error handling.
  
Screenshots
![image](https://github.com/user-attachments/assets/fc687883-bf29-4853-b890-06cad4c20d00)

How It Works
This calculator allows you to input numbers and arithmetic operations (+, -, *, /). You can click the buttons on the screen to perform calculations or delete mistakes with the "DE" button. The "AC" button will reset the entire input.

When you press the "=" button, the expression is evaluated, and the result is displayed. Invalid expressions return an error.

HTML Structure
- The calculator consists of a simple form that includes buttons for numbers, operators, and actions.
- The `input` fields are used to display the user's input and output of calculations.

CSS Styling
- The calculator is styled using **CSS** for a modern, minimalistic look.
- The layout is responsive and adjusts to different screen sizes.

JavaScript Logic
- The calculator's core logic is implemented using **JavaScript**.
- The `eval()` function has been replaced with a more secure and safer method using `math.evaluate()` for better validation and error handling.
- Error handling prevents invalid expressions from being evaluated, displaying an error message when needed.

Getting Started

Prerequisites
You need a modern web browser to run this calculator locally.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/calculator-project.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd calculator-project
   ```

3. **Open `index.html` in your browser**.

Usage
- Click on the number and operator buttons to input an expression.
- Use the "AC" button to clear the screen and the "DE" button to delete the last character.
- Press "=" to evaluate the expression.

Technologies Used
- **HTML5** for the markup
- **CSS3** for styling
- **JavaScript** for the calculator logic

Future Improvements
- Adding advanced operations like square root, percentage, and exponentiation.
- Implementing keyboard support for easier input.
- Adding a theme switcher for light and dark modes.

License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Acknowledgments
- Thanks to [math.js](https://mathjs.org/) for the math evaluation library used to safely process expressions.
