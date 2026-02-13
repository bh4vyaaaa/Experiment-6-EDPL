#Python Conditional Statements: Theory and Logic
##Name: Bhavya Pandya

##PRN: 25070123139

###Batch: E&TC A1

Overview
Conditional statements are fundamental control flow structures that allow a program to execute different blocks of code based on whether a specific condition evaluates to True or False. In Python, these decisions are driven by boolean logic and comparison operators.

1. The if Statement
The if statement is the most basic form of control flow. It tests a condition; if the condition is met (True), the indented block of code directly following it is executed. If the condition is False, the program simply skips that block.

2. The if-else Statement
The if-else structure provides a dual-path logic. It ensures that one of two blocks will always execute. When the if condition fails, the code defaults to the else block. This is used for binary decisions where there is a clear alternative to the primary condition.

3. The if-elif-else Ladder
The elif (short for "else if") statement allows for multiple, sequential condition checks. This is more efficient than using multiple independent if statements because Python stops evaluating once it finds the first True condition. The optional else block at the end acts as a "catch-all" if none of the preceding conditions are satisfied.

4. Nested Conditionals
Conditionals can be "nested" within one another to handle complex, multi-layered decision trees. A nested if is only evaluated if the outer if condition has already passed. While powerful, excessive nesting can reduce code readability and should be used judiciously.

5. Logical and Comparison Operators
Conditional logic relies on two types of operators:

Comparison Operators: Used to compare values (== for equality, != for inequality, >, <, >=, <=).

Logical Operators: Used to combine multiple conditions:

and: Returns True if both conditions are True.

or: Returns True if at least one condition is True.

not: Reverses the boolean state of a condition.

6. Truthiness and Falsiness
In Python, conditions do not always have to be explicit comparisons. Objects have inherent "truthiness." For example, non-zero numbers and non-empty strings/lists are considered True, while 0, None, and empty containers ([], {}, "") are considered False.

Structural Requirements
Indentation: Unlike many other languages that use curly braces, Python relies strictly on indentation (usually 4 spaces) to define the scope of a conditional block.

The Colon (:): Every conditional header (if, elif, else) must terminate with a colon to signify the start of the indented suite.
