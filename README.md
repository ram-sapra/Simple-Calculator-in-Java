# Simple-Calculator-in-Java
● The goal of this program is to create a simple calculator with a GUI where users can input numbers, perform basic arithmetic operations, and view the results on the display. The calculator is created using Java's Swing library, and the arithmetic operations are performed based on the user's inputs.

This Java code creates a simple calculator GUI application using Swing. Here's a summary of what the code does:

1. Imports required packages: The code imports the necessary packages for creating graphical user interfaces (GUIs) in Java, including AWT and Swing.

2. Defines the `Calculator` class: The `Calculator` class implements the `ActionListener` interface to handle button actions. It sets up the calculator's GUI components and defines the logic for button clicks.

3. GUI Initialization:
   - The `Calculator` class creates a `JFrame` to hold the calculator interface.
   - It defines text fields, number buttons, and function buttons (add, subtract, multiply, divide, decimal point, equals, delete, clear, negative number).
   - The buttons are organized using a `JPanel` with a grid layout.

4. Button Actions:
   - The class implements the `actionPerformed` method to handle button clicks.
   - Number buttons and decimal point button append their corresponding values to the text field.
   - Function buttons (add, subtract, multiply, divide) store the first number and selected operator, then clear the text field.
   - The equals button calculates the result based on the stored operator and the second number, and displays the result.
   - The clear button resets the text field.
   - The delete button removes the last character from the text field.
   - The negative button toggles the sign of the displayed number.

5. `main` method:
   - The `main` method in the `Calc` class creates an instance of the `Calculator` class, initializing the GUI.

Overall, this code creates a basic calculator application with a graphical user interface that allows users to perform arithmetic operations on numbers. It uses Swing components and event handling to achieve this functionality.
## Screenshots:
#### The picture shows the multiplication of 63 and 48:
![image](https://github.com/ram-sapra/Simple-Calculator-in-Java/assets/143723327/17a5f990-d13a-45f8-af24-1216ec477c97)


#### This picture shows the multiplication of (-3) and 69: 
![image](https://github.com/ram-sapra/Simple-Calculator-in-Java/assets/143723327/55853caf-5a24-420c-a232-7ac5d5dec998)

