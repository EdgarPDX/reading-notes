Reading
Here are the chapters to read before class:

From the Duckett JS book:

JavaScript book, Ch. 10, “Error Handling & Debugging”
- The Console & Dev Tools: Tools built into the browser that help you hunt for errors.
- Order of execution: the order in which processes are executed
- Execution Context :
    - Global Context: code that is in the script but not in a function. There is only one global context in any page.
    - Function Context: Code that is being run within a function context.
    - Eval Context: Text is executed like code in an internal function call eval()
Variable Scope:
    - Global Scope: variable that is declared outside of a function, it can be used within the page. Needs to be exported to be used in other pages.
    - Function-Level Scope: if a function is declared within a function, it can only be used within that function
The Stack: 
    - javascript gets interpreted on line of code at a time. When the code needs information from another page. When new code is stacked  it creates a new execution context.
Execution context and Hoisting:
    - Prepare:
        - The New Scope is created
        - Variables, Functions and arguments are created
        The value of the THIS keyword is determined
    - Execute:
        - Now it can assign values to variable
        - Reference functions and run their code
        - Execute Statements
    -Error Objects:
        - Syntax Errors: usually caused by a typo. Caused by incorrectly using language rules
        