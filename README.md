This code defines a simple calculator web application using HTML, CSS, and JavaScript. Let's break down the key components:

### HTML (index.html):
- The HTML structure defines a basic webpage with a calculator interface.
- The `<head>` section includes meta tags for character set and viewport settings, and it links to a Google Fonts stylesheet for the 'Poppins' font.
- The main content is within the `<body>` tag, containing a calculator div with various buttons for numbers, operators, and actions like clear (AC) and delete (DEL).
- The `<script>` tag includes a reference to an external JavaScript file, 'script.js', which contains the logic for the calculator.

### CSS (style.css):
- Resets some default styles using the universal selector (*).
- Sets the body to full width and height, centers content using flexbox, and applies a gradient background.
- Styles the calculator container with borders, padding, border-radius, and a box shadow.
- Styles the input box and buttons, applying a transparent background, box shadow, and font styles.
- Specific styling for the equals button (`equalBtn`) and operator buttons.

### JavaScript (script.js):
- Retrieves the input element and all buttons.
- Adds a click event listener to each button, defining behavior for different button types.
- The calculator logic is implemented using a string (`string`) to store the input expression.
- When a button is clicked, it checks the button's innerHTML to determine the action.
  - '=': Evaluates the expression using `eval()` and updates the input.
  - 'AC': Clears the input string.
  - 'DEL': Removes the last character from the input string.
  - Other buttons: Appends the corresponding value to the input string.

### Overall Description:
- The web application provides a simple calculator interface where users can input mathematical expressions and perform basic calculations.
- Styling is done with a modern, sleek design using gradients and shadows.
- The calculator's functionality is implemented using JavaScript to handle user input and perform calculations dynamically.

Note: Using `eval()` for calculations can have security implications, and it's generally recommended to use safer alternatives for expression evaluation in a production environment.
