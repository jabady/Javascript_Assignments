Name the three ways to declare a variable
    Three ways of creating a variable are through declaring the statements called let, const, and var.
Which of the three variable declarations should you avoid and why?
    The variable declaration var should be avoided as it uses old scripting. Var has no block scoping. As such it can appear outside of loops if you create a variable through var. Var can also be redeclared. Var variables can be declared AFTER being used (this makes code very confusing as you're hunting for when a variable is created).
What rules should you follow when naming variables?
    Name should only contain letters, digits, and spaces indicated by _. The first character can never be a digit. Do camelCase for lets (with no spaces) and underscores for spaces on const variables. 
What should you look out for when using the + operator with numbers and strings?
    Beware of concatenation. + before a variable also converts a string to a number.  
How does the % operator work?
    It is the modulo operator. It shows the remainder of a division problem. 
Explain the difference between == and ===.
    == checks if the value is the same regardless of the type, === checks the type and value. So "1" == 1 returns true but "1" === 1 returns false. 
When would you receive a NaN result?
    Doing arithmetic with strings (exception of + or strings that contain numbers)
How do you increment and decrement a number?
    You increment using ++ and decrement with --. Both can be done before or after a variable. 
Explain the difference between prefixing and post-fixing increment/decrement operators.
    Prefixing adds an incrementation BEFORE the arithmetic. Post fixing is done AFTER the arithmetic. 
What is operator precedence and how is it handled in JS?
    Operator precedence is the execution order. Basicaly PEMDAS but for operators. We have a precedence table to let us know how it is handled. 
How do you access developer tools and the console?
    You access developer tools by right clicking inspect. Go to developer tools, and select the console tab. 
How do you log information to the console?
    Console.log().
What does unary plus operator do to string representations of integers?
    Converts them to numerical representations. It works like Number().