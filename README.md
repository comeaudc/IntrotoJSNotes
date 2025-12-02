# Intro To JavaScript
-   High level - no access to CPU process (read/write to CPU)
-   Weakly typed - do not need to declare datatypes and can be fluid
-   Interpreted language by the browser NOT compiled

## Running JS File with Node.js
-   In terminal execute, `node fileName.js`

## Basic JS Grammar
-   case-sensistive
-   read top -> bottom, left -> right
-   statements - each individual action is considered a statement ended with a semi colon;
-   JS Comments:
    -   // - single line comments
    -   /**/ - multiline comments
-   Variables - a container in memory, that we can give a name and can store/retrieve values for our program
-   Code Blocks - are delineated/defined with curly braces {}


## Implementing JS/JS Files into HTML
-   Script tags should be incoporated either at the end of the body OR in head with a `defer` keyword.
![HTEMl JS](./embedJS.png)

## Primitive JS Data Types:
-   Numbers Types:
    -   integer (INT) - whole numbers, no decimal at all
    -   float - any number with decimal values
-   String - sequence of characters, including spaces, enclosed quotes (double, single, backtics)
-   Char - single character string
-   Boolean (Bool) - true / false
-   Null - does not have any datatype of value assigned. Null MUST BE ASSIGNED.
-   Undenfined - indicates a variable has NO value.

## Advanced JS DataTypes:
-   BigInt - for extremely large numbers

## let - keyword
-   block-scoped
-   reassignable
-   NOT redeclarable
-   is subject to hoisting

## cont - keyword
-   block-scoped
-   NOT reassignable
-   NOT redeclarable
-   is subject to hoisting

## Vocab:
-   literals - Numberic, Strings, Booleans values declared without a variable. Most often used for logic or console.log()
-   typeof - keyword used to find the type of a variable of literal. Always returns a string (can be used for compairison logic)

## Arithmetic operators
-   +  addition
-   - subtraction
-   * multiplication
-   / division
-   % modulous (mod) - whole numbe remaining after division
-   ** exponentiation (to the power of)