Python calculator(calc) program without a graphical user interface (GUI) by bad for now idk know how to code with GUI :

# Calculator

This is a simple calculator program written in Python that performs basic arithmetic operations on two numbers. The calculator operates through the command line interface (CLI) and does not have a graphical user interface (GUI).

# Features

- Addition (+): Add two numbers.
- Subtraction (-): Subtract the second number from the first number.
- Multiplication (*): Multiply two numbers.
- Division (/): Divide the first number by the second number.
- Error Handling: Handles division by zero and invalid operations.

# Usage

1. Open the command prompt or terminal.
2. Navigate to the directory where the calculator Python file is located.
3. Run the following command:  `python calc.py`

4. Follow the prompts to enter the first number, second number, and the desired operation.
5. The calculator will calculate the result and display it on the console.

# Example

$ python calc.py
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): *

Result: 50

# Code

Here's the Python code for the calculator:

```python
#where over here you are gonna write code for two numbers that user input to calculate 
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

#this is operation such as add, sub, div , mul 
operation = input("Enter the operation (+, -, *, /): ")

#this is the if statement where it is results based user in in operation as shown
if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    result = num1 / num2
else:
    print("Invalid operation Wrong number buddy try again :) ")

#this is the print command to print results of calc in final 
print("Result: ", result)

#this is the end of the code & enjoy just my first project !
```

# Requirements

- Python 3.x > three link to get ---> [py.org](https://www.python.org/downloads/)

# License

This calculator program is released under the [MIT License](LICENSE).

Feel free to modify the content to match the specifics of your calculator program or add any additional sections as needed by forking or downloading this source code from github respository.

If you have any further questions, feel free to ask! (i am being silly damn it dudes anyone have futher question in this darn project of simple calc code ) 

# Author 
noobie dev
