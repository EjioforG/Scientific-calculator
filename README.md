NAME: EJIOFOR GODWILL UGOCHUKWU
MATRIC NO: U23CYS1029
DEPARTMENT: CYBERSECURITY
LEVEL: 200L


How the Code Works

1. Creates the Calculator GUI

A JFrame window with a JTextField display.

Buttons are dynamically created and arranged in a GridLayout.



2. Handles Button Clicks (actionPerformed)

Numbers and operators are added to currentInput.

Functions like sin, cos, √ append respective expressions.

AC clears everything, C clears recent input, and = evaluates the expression.

The "Rad/Deg" button toggles angle modes.



3. Evaluates Expressions (evaluateExpression)

Converts infix expressions to postfix using the Shunting Yard Algorithm.

Uses a stack to evaluate the postfix expression.

Supports functions (sqrt, log, sin, cos), operators (+, -, *, /, ^), and factorial.



4. Displays the Result

If valid, the result is shown.

If invalid, an error message is displayed.




The program provides a fully functional scientific calculator with GUI interaction and accurate mathematical evaluations.

