# 0x02. ES6 classes

## Resources
**Read or watch:**

- [Classes](https://intranet.alxswe.com/rltoken/ke2dSL31JbpAUBW0qWE9WA)
- [Metaprogramming](https://intranet.alxswe.com/rltoken/6OgF5QGbYclp_cwATfq-0g)


## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- How to define a Class
- How to add methods to a class
- Why and how to add a static method to a class
- How to extend a class from another
- Metaprogramming and symbols

## Requirements
**General**

- All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the js extension
- Your code will be tested using the [`Jest Testing Framework`](https://intranet.alxswe.com/rltoken/ECZpKsJ3fm1qRA7lDyhd_Q)
- Your code will be analyzed using the linter [`ESLint`](https://intranet.alxswe.com/rltoken/Ttd9w5jERwTErJW3DDbVoQ) along with specific rules that we'll provide
- All of your functions must be exported

## Setup
**Install NodeJS 12.11.x**
(in your home directory):

```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

```
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```

## Install Jest, Babel, and ESLint
in your project directory:

- Install Jest using: `npm install --save-dev jest`
- Install Babel using: `npm install --save-dev babel-jest @babel/core @babel/preset-env`
- Install ESLint using: `npm install --save-dev eslint`

## Finally…
Don’t forget to run `npm install` from the terminal of your project folder to install all necessary project dependencies.
