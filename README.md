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


## 📌 JavaScript Line Length and Line Breaks

-   For best readability, programmers often like to avoid code lines longer than 80 characters.  Although with large modern screens nowadays the need to do this is less common.
-   If a JavaScript statement does not fit on one line, the best place to break it is after an operator:

    For example:

    ```js
    document.getElementById("demo").innerHTML =
    "Hello Dolly!";
    ```


## 📌 JavaScript Code Blocks

-   JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.
-   The purpose of code blocks is to define statements to be executed together.
-   One place you will find statements grouped together in blocks, is in JavaScript functions:
    For example


    ```js
    function myFunction() {
    document.getElementById("demo1").innerHTML = "Hello Dolly!";
    document.getElementById("demo2").innerHTML = "How are you?";
    }
    ```

## 📌 JavaScript Code Blocks

-   It's quite common for JavaScript statements to start with a keyword which identifies the JavaScript action to be performed.

| Keyword   | Description    |
|-----------|------------------|
| Jvar      |  Declares a variable   |
| let       |  Declares a block variable      |
| const     |  Declares a block constant |
| if        | Marks a block of statements to be executed if a condition is true |
| switch    | Marks a block of statements to be executed in different cases |
| for       | Marks a block of statements to be executed in a loop |
| function  | Declares a function |
| return    | Exits a function |
| try       | Implements error handling to a block of statements |



## 📌 JavaScript Comments 

-   Not all JavaScript statements are "executed".
-   Code after double slashes // or between /* and */ is treated as a comment.
-   Comments are ignored, and will not be executed:

    For example:

    ```js
    let x = 5; // I will be executed
    
    // x = 6; I will NOT be executed 

    ```

## 📌 Multi-line Comments

-   Multi-line comments start with /* and end with */.
-   Multi-line comments happen when we comment out multiple lines of JavaScript.
-   Any text between /* and */ will be ignored by JavaScript.
-   This example uses a multi-line comment (a comment block) to explain the code:

    ```js
    /*
    The code below will change
    the heading with id = "myH"
    and the paragraph with id = "myP"
    in my web page:
    */
    document.getElementById("myH").innerHTML = "My First Page";
    document.getElementById("myP").innerHTML = "My first paragraph.";
    ```

## 📌 JavaScript Identifiers 

-   Identifiers are JavaScript names.
-   Identifiers are used to name variables and keywords, and functions.
-   The rules for legal names are the same in most programming languages.
-   A JavaScript name must begin with:

    -   A letter (A-Z or a-z)
    -   • A dollar sign ($)
    -   • Or an underscore (_)

-   Subsequent characters may be letters, digits, underscores, or dollar signs

    ###  Special Note

    Numbers are not allowed as the first character in names.

    This way JavaScript can easily distinguish identifiers from numbers.




## 📌 JavaScript is ALWAYS Case Sensitive

-   All JavaScript identifiers are case sensitive.
-   For example:  The variables `lastName` and `lastname`, are two different variables:

    ```js
    let lastname, lastName;
    lastName = "Doe";
    lastname = "Peterson";
    ```

## 📌 JavaScript and Camel Case

-   Historically, programmers have used different ways of joining multiple words into one variable name:

    ### Hypens  -  NOT ALLOWED

    first-name, last-name, master-card, inter-city

- Hyphens are not allowed in JavaScript. They are reserved for subtractions.

    ### Underscore  (allowed)

    first_name, last_name, master_card, inter_city.

    ### Upper Camel Case  -  aka Pascal Case  (allowed)

    FirstName, LastName, MasterCard, InterCity

    ### Lower Camel Case

    firstName, lastName, masterCard, interCity

-   JavaScript programmers tend to use lower camel case that starts with a lowercase letter:



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
