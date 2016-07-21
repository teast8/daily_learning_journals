# LJ Code 201 Day - 3

“Tell me and I forget Teach me and I remember. Involve me and I learn.”

Javascript was main topic of discussion today. Everything in Javascript is basically a statement.
Statements should end with semi-colons.
Comments are best practices in coding. (one line comment //comment)

I  also learned about the Array Methods today.


Notes from todays class



Operators

- Assignment operators are the equal sign that assign a value to a variable
    - color = 'beige';
- Arithmetic operators perform basic math
    - area = 3*2; returns 6
    - % is the modulus operator, which divides two values and returns the remainder
    - ++ is the increment operator, which adds 1
- String operators combine two strings, like with concatenation
    - greeting = ‘Hi ‘ + ‘Molly!'
- Comparison operators compare two values and return a boolean
    - buy = 3>5; returns false
    - == (the loose equals) checks to see whether the values of two elements are equal
        - ‘8’ = 8 will return true because they both have the value of 8, even though one is a string
        - Loose equals performs type coercion— it coerces them into being the same type before evaluation.
            - Type coercion does not work with booleans! “true” == true will NOT return true.
        - Loose equals is unpredictable! Best to steer clear.
    - === (the strict equals) checks to see whether the values and types of two elements are equal
        - ‘8’ === 8 will return false because the type is different even though the value is the same
    - !== returns “not equal to"
- Logical operators combine expressions and return a boolean
    - buy = (5>3) && (2<4); evaluates to true
