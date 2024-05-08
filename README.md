# Milestone 1: Input Handling Implementation
## Grammar Rules
The grammar for the language supported by the parser is as follows:

* Operators: Addition (+), Subtraction (-), Multiplication (*), Division (/)
* Functions: Trigonometric functions (sin, cos, tan), Square root (sqrt)
* Variables: Single-letter variables (x, y, z)
* Parentheses: Open and close parentheses for grouping expressions

## Input Handling Implementation
* Prompt User Input: A function or method prompts the user to enter an arithmetic expression.
* Tokenization: The input string is tokenized by identifying numbers, operators, functions, variables, and parentheses based on the grammar rules.
* Regular Expressions: Regular expressions and string manipulation techniques are used to extract tokens efficiently.
* Error Handling: Edge cases and error scenarios, such as invalid characters or mismatched parentheses, are handled to prevent crashes and ensure robustness.
* Token Storage: Tokens are stored in a data structure like a list or a queue to facilitate parsing and further processing in subsequent milestones.

## Usage
To run the input handling implementation:
1. Execute the provided code in a Python environment.
2. Enter an arithmetic expression when prompted.
3. The tokenizer will tokenize the input expression and display the tokens.
