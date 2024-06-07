# 0x00. ES6 Basics

-------------

## Description

This project focuses on understanding and implementing features introduced in ECMAScript 6 (ES6). Through a series of tasks, to learn and practice new syntax and capabilities provided by ES6, including block-scoped variables, arrow functions, template literals, default parameters, and more.

## Learning Objectives

- Explain core ES6 concepts
- Implement ES6 features in your code
- Utilize ESLint for code linting

## Requirements

- All files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A [README.md](../README.md) file at the root of the project folder is mandatory
- Your code should use the .js extension
- Your code will be tested using the Jest Testing Framework
- Your code will be analyzed using the linter ESLint along with specific rules provided
- All functions must be exported

## **Setup**

### Prerequisites

- Ubuntu 18.04 LTS
- NodeJS 12.11.x

### Installation

1. Install NodeJS:

   ```bash
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y

    ```

2. Check NodeJS and npm versions:

    ```bash
    nodejs -v
    # v12.11.1

    npm -v
    # 6.11.3
    ```

3. Install Jest, Babel, and ESLint:

   Navigate to your project directory and run:

    ```bash
    npm install
    ```

### Configuration Files

Ensure the following configuration files are in your project directory:

- `package.json`
- `babel.config.js`
- `.eslintrc.js`

## Task

0. Const or Let?
   Practice using const and let to declare variables

   - File: [`0-constants.js`](0-constants.js)

1. Block Scope
   Explore how block scope impacts variable accessibility

   - File: [`1-block-scoped.js`](1-block-scoped.js)

2. Arrow Functions
   Implement arrow functions for concise function definitions

   - File: [`2-arrow.js`](2-arrow.js)

3. Parameter Defaults
   Utilize default parameter values to enhance function flexibility

   - File: [`3-default-parameter.js`](3-default-parameter.js)

4. Rest Parameter Syntax
   Leverage rest parameters to capture an indefinite number of arguments

   - File: [`4-rest-parameter.js`](4-rest-parameter.js)

5. The wonders of spread syntax
   Employ spread syntax to simplify array and object manipulation

   - File: [`5-spread-operator.js`](5-spread-operator.js)

6. Take advantage of template literals
   Utilize template literals for enhanced string interpolation

   - File: [`6-string-interpolation.js`](6-string-interpolation.js)

7. Object property value shorthand syntax
   Implement object property value shorthand syntax

   - File: [`7-getBudgetObject.js`](7-getBudgetObject.js)

8. No need to create empty objects before adding in properties
   Utilize computed property names for dynamic object property creation

   - File: [`8-getBudgetCurrentYear.js`](8-getBudgetCurrentYear.js)

9. ES6 method properties
    Define object methods using ES6 method properties

    - File: [`9-getFullBudget.js`](9-getFullBudget.js)

10. For...of Loops
    Employ for-of loops for iterating over iterables

    - File: [`10-loops.js`](10-loops.js)

11. Iterator
    Create an iterator object for traversing report data

    - File: [`11-createEmployeesObject.js`](11-createEmployeesObject.js)

12. Let's create a report object
    Construct a report object to organize employee data

    - File: [`12-createReportObject.js`](12-createReportObject.js)

### Advanced Tasks

13. Iterating through report objects (Advanced)
    Implement a function to iterate through employee data in the report object

    - File: [`100-createIteratorObject.js`](100-createIteratorObject.js)

14. Iterate through object (Advanced)
    Design a function to return a string representation of all employee names

    - File: [`101-iterateThroughObject.js`](101-iterateThroughObject.js)

## Resources

- [ECMAScript 6 - ECMAScript 2015](https://ecma-international.org/publications-and-standards/standards/ecma-262/)
- [JavaScript ES6 documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [ESLint documentation](https://eslint.org/)