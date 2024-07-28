# alx-backend-javascript

## Project Overview

This project provides a comprehensive introduction to Node.js backend development. It encompasses fundamental concepts such as executing JavaScript with Node.js, file system operations, HTTP server creation, and routing with Express.js. Through hands-on exercises, learners will gain practical experience in building robust backend applications.

## Learning Objectives

Upon completion of this project, i was able to learn how to:

* Execute JavaScript code effectively using Node.js
* Utilize Node.js modules for code organization and reusability
* Perform synchronous and asynchronous file I/O operations
* Create and manage HTTP servers using both the built-in HTTP module and Express.js
* Implement RESTful API endpoints using Express.js
* Leverage ES6 syntax for modern JavaScript development
* Employ Nodemon for efficient development workflows

## Project Structure

The project is organized into the following directories and files:

```
0x05-Node_JS_basic/
├── 0-console.js
├── 1-stdin.js
├── 2-read_file.js
├── 3-read_file_async.js
├── 4-http.js
├── 5-http.js
├── 6-http_express.js
├── 7-http_express.js
├── full_server/
│   ├── controllers/
│   │   ├── AppController.js
│   │   └── StudentsController.js
│   ├── routes/
│   │   └── index.js
│   ├── server.js
│   └── utils.js
├── database.csv
├── package.json
├── .eslintrc.js (optional)
├── .babelrc (optional)
└── README.md
```

## Project Setup

1. Clone the repository:
   ```bash
   git clone [link to your GitHub repository](link here)
   ```
2. Navigate to the project directory:
   ```bash
   cd 0x05-Node_JS_basic
   ```
3. Install project dependencies:
   ```bash
   npm install
   ```

## Development Environment

* **Recommended Editors:** Visual Studio Code, Vim, Emacs
* **Node.js Version:** 12.x.x

## Testing

* Jest is used for unit testing. Run `npm run test` to execute tests.
* ESLint is used for code linting. Run `npm run lint` to check code style.
* To run the full test suite, execute `npm run full-test`.

## Running the Project

* For basic tasks (0-5):
  ```bash
  npm start
  ```
* For the organized server structure (full_server):
  ```bash
  npm run dev
  ```

The server will be accessible at http://localhost:1245 by default.
