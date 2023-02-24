This code creates a simple calculator GUI using the tkinter library in Python. It defines a Calculator class that creates a GUI window with a display widget, number buttons, operation buttons, and a power button.

The create_button() method creates a tkinter Button widget with the specified text, row, column, padding, font, background color, and command (a lambda function that calls the button_click() method with the button's text as an argument). The button is then added to the calculator window using the grid() method.

The button_click() method is called whenever a button is clicked. It performs different actions depending on the button's text. If the text is "=", it evaluates the expression in the display widget using the eval() function and displays the result. If the text is "C", it clears the display widget. If the text is "√", it calculates the square root of the number in the display widget using the math.sqrt() function. If the text is "x²", it calculates the square of the number in the display widget. If the text is "OFF", it destroys the calculator window. Otherwise, it appends the button's text to the end of the display widget.

Finally, the code creates an instance of the Calculator class and starts the mainloop of the tkinter window, which waits for user input until the window is closed or destroyed.
