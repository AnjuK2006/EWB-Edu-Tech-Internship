# JavaScript Assignments and Capstone Project

## Overview

This repository contains JavaScript assignments and a capstone project developed to practice fundamental programming concepts. The assignments cover JavaScript basics, user input, operators, conditional statements, loops, functions, and array methods.

The capstone project, **Interactive Product Inventory & Analytics Dashboard**, combines these concepts to manage products, calculate inventory values, and generate reports.

## Technologies Used

- JavaScript
- HTML browser environment
- JSFiddle
- Browser Developer Console

---

## Assignment 1: JavaScript Basics and Output

### Objective
Understand JavaScript fundamentals, variables, data types, and output statements.

### Concepts Covered
- Variables using `let`, `const`, and `var`
- Basic data types: strings, numbers, and booleans
- Output using `console.log()`
- Basic arithmetic operations
- JavaScript syntax

### Sample Code

```javascript
const name = "Anju";
const age = 20;

console.log("Name: " + name);
console.log("Age: " + age);
console.log("Sum: " + (10 + 20));
```

### Sample Output

```text
Name: Anju
Age: 20
Sum: 30
```

### Learning Outcome
Learned how to declare variables, work with basic data types, perform simple calculations, and display output.

---

## Assignment 2: User Input and Operators

### Objective
Accept user input and perform calculations using JavaScript operators.

### Concepts Covered
- `prompt()` for user input
- `Number()` for type conversion
- Arithmetic operators
- Assignment operators
- `console.log()` for displaying results

### Learning Outcome
Learned how to collect user input, convert values to numbers, and perform calculations.

---

## Assignment 3: Conditional Statements

### Objective
Make decisions based on conditions.

### Concepts Covered
- `if` statement
- `if-else` statement
- `else-if` statement
- Comparison operators
- Logical operators
- `switch` statement

### Learning Outcome
Learned how to execute different blocks of code depending on given conditions.

---

## Assignment 4: Loops and Control Statements

### Objective
Repeat operations and control the flow of program execution.

### Concepts Covered
- `for` loop
- `while` loop
- `break` statement
- `continue` statement

### Learning Outcome
Learned how to repeat tasks, search through data, and control loop execution.

---

## Assignment 5: Functions

### Objective
Organize code into reusable blocks.

### Concepts Covered
- Function declarations
- Function parameters and return values
- Arrow functions
- Local variables and scope
- Reusable calculations

### Learning Outcome
Learned how to create reusable functions, pass arguments, return results, and organize code.

---

## Assignment 6: JavaScript Array Methods

### Objective
Process and transform collections of data.

### Concepts Covered
- Arrays and objects
- `forEach()` to process each item
- `filter()` to select matching items
- `map()` to transform data
- `reduce()` to calculate a single result

### Learning Outcome
Learned how to process arrays, filter data, transform values, and calculate totals efficiently.

---

## Capstone Project: Interactive Product Inventory & Analytics Dashboard

### Project Description

The Interactive Product Inventory & Analytics Dashboard is a JavaScript application that allows users to add products, categorize them based on price, calculate total inventory value, filter affordable products, and generate formatted inventory reports.

The application begins with two products, Laptop and Mouse. Users can enter a new product name and price, such as Monitor and $150, to update the inventory.

### Features

- **User Input:** Accepts product names and prices using `prompt()`.
- **Input Validation:** Checks product details before adding them.
- **Product Categorization:** Classifies products as Budget, Standard, or Premium.
- **Inventory Processing:** Displays product details using `forEach()`.
- **Product Search:** Uses loops and `break` to search for products.
- **Loop Control:** Uses `continue` to skip invalid items during calculations.
- **Financial Analytics:** Calculates the total inventory value.
- **Product Filtering:** Finds products priced below $200.
- **Formatted Reports:** Converts product names to uppercase using `map()`.
- **Discount and Tax Calculation:** Calculates final prices using configurable discount and tax percentages.

### Product Categories

| Price Range | Category |
|---|---|
| Below $50 | Budget |
| $50 to below $200 | Standard |
| $200 and above | Premium |

### Sample Input

```text
Product Name: Monitor
Product Price: 150
```

### Sample Output

```text
--- Initializing Inventory System ---
[Prompt executed: User adds "Monitor" at "$150"]

--- Processing Inventory Roster (forEach) ---
* Item: Laptop ($800) -> Category: Premium
* Item: Mouse ($25) -> Category: Budget
* Item: Monitor ($150) -> Category: Standard

--- Financial Analytics ---
Total Inventory Value: $975
Filtered Affordable Items (Under $200): ["Mouse","Monitor"]

Formatted Report List: ["LAPTOP: $800","MOUSE: $25","MONITOR: $150"]
```

### JavaScript Concepts Demonstrated

- Variables and data types
- User input and type conversion
- Conditional statements and `switch`
- Loops, `break`, and `continue`
- Functions and arrow functions
- Arrays and objects
- `forEach()`, `filter()`, `map()`, and `reduce()`
- Input validation
- Arithmetic calculations
- Template literals and JSON formatting

---

## How to Run the Assignments and Project

1. Open [JSFiddle](https://jsfiddle.net/).
2. Paste the JavaScript code into the **JavaScript panel**.
3. Click **Run**.
4. Enter the requested values in any prompt windows.
5. Open the browser developer console using **F12 → Console** to view the output.

Repeat these steps for each assignment and the capstone project.

## Learning Outcomes

By completing these assignments and the capstone project, I practiced:

- Writing and executing JavaScript programs.
- Collecting and validating user input.
- Using operators and conditional statements.
- Working with loops and functions.
- Processing arrays and objects.
- Performing calculations and analyzing inventory data.
- Generating formatted reports using JavaScript array methods.

## Conclusion

These assignments helped build a foundation in JavaScript programming. The capstone project applies the concepts learned throughout the assignments to a practical inventory management and analytics use case.

