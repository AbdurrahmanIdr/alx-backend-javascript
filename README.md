# **ALX Backend JavaScript**

---------------------------

This repository contains projects and tasks to learn and master the fundamentals of JavaScript ES6 (ECMAScript 2015) and its various features. Each task aims in solidifying understanding of modern JavaScript practices, from basic syntax to advanced concepts.

## **Table of Contents**

- Introduction
- Resources
- Projects
- Setup
- Usage
- Contributing
- License

## **Introduction**

This repository is part of the ALX Backend JavaScript curriculum. It focuses on the following JavaScript ES6 concepts:

- Constants and variables
- Block-scoped variables
- Arrow functions
- Default parameters
- Rest and spread syntax
- String templating
- Object creation and properties
- Iterators and for-of loops

## **Resources**

To complete the projects, you will need to read or watch the following resources:

- ECMAScript 6 - ECMAScript 2015
- Statements and declarations
- Arrow functions
- Default parameters
- Rest parameter
- Iterables and Iterators

## **Projects**

1. [ES6 Basics](0x00-ES6_basic/README.md)

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

## **Usage**

To run and test your code, use:

```bash
npm run dev <filename>
```

## **Contributing**

Contributions are welcome! Please follow these steps:

- Fork this repository.
- Create a branch: `git checkout -b <branch_name>`.
- Make your changes and commit them: `git commit -m '<commit_message>'`.
- Push to the original branch: `git push origin <project_name>/<location>`.
- Create the pull request.
- Alternatively, see the GitHub documentation on creating a pull request.

## **License**

This project is licensed under the [MIT License](LICENCE) - see the LICENSE file for details.
