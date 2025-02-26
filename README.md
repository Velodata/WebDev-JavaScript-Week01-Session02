# JavaScript Language Basics

Welcome to Week 01, Session 02!

In this lesson, we will cover:

## 📌 JavaScript Statements

-   JavaScript programs are made up of **statements**.
-   Statements **end with a semicolon `;`** (optional but recommended).
-   Example:

    ```js
    let message = "Hello, world!";
    console.log(message);
    ```

-   JavaScript statements are composed of:
    Values, Operators, Expressions, Keywords, and Comments.
-   For Example:
    This next statement tells the browser to write "Hello Dolly." inside an HTML element with id="demo":
    ```js
    document.getElementById("demo").innerHTML = "Hello Dolly.";
    ```
-   Most JavaScript programs contain many JavaScript statements.
    The statements are executed, one by one, in the same order as they are written.
    JavaScript programs (and JavaScript statements) are often called JavaScript code.

    ### Semicolons

    Semicolons separate JavaScript statements.

    Add a semicolon at the end of each executable statement

    Here are some examples...

    ```js
    let a, b, c; // Declare 3 variables
    a = 5; // Assign the value 5 to a
    b = 6; // Assign the value 6 to b
    c = a + b; // Assign the sum of a and b to c
    ```

## 📌 JavaScript White Space

-   JavaScript ignores multiple spaces. You can add white space to your script to make it more
    readable.
-   For example: The following statements are equivalent in JavaScript:

    ```js
    let person  =  "Hege";
    let person = "Hege";
    ```

    A good practice is to put spaces around operators ( = + - * / ):

    For example:

    ```js
    let x = y + z;
    ```

## 📌 JavaScript Character Set

-   JavaScript uses the Unicode character set.

-   Unicode covers (almost) all the characters, punctuations, and symbols in the world.

-   For a closer look, please study our Complete Unicode Reference.

## 📌 JavaScript Expressions

-   An expression is a combination of values, variables, and operators, which computes to a value.
-   The computation is called an evaluation.
-   For example, 5 _ 10 evaluates to 50:
    5 _ 10
-   Expressions can also contain variable values:
    x \* 10
-   The values can be of various types, such as numbers and strings.
    For example, "John" + " " + "Doe", evaluates to "John Doe":
    "John" + " " + "Doe"
