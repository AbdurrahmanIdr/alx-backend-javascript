# 0x01. ES6 Promises

This project focuses on ES6 Promises, a powerful feature in JavaScript for handling asynchronous operations. The tasks will helps in understand and use Promises effectively in various scenarios.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without the help of Google:

- What Promises are and why they are used.
- How to use the `then`, `resolve`, and `catch` methods.
- How to use every method of the Promise object.
- How to handle errors using `throw` and `try/catch`.
- How to use the `await` operator and `async` functions.

## Setup

1. Install NodeJS v22.1.0:

   ```sh
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y
   ```

   Verify the installation:

   ```sh
   node -v
   v22.1.0
   npm -v
   10.7.0
   ```

2. Clone the repository and navigate to the project directory:

   ```sh
   git clone https://github.com/AbdurrahmanIdr/alx-backend-javascript.git
   cd alx-backend-javascript/0x01-ES6_promise
   ```

3. Install Jest, Babel, and ESLint:

   ```sh
   npm install
   ```

## Project Structure

- `0-promise.js`: Contains a function that returns a Promise.
- `1-promise.js`: Contains a function that returns a resolved or rejected Promise based on a boolean parameter.
- `2-then.js`: Contains a function that handles a Promise with `then` and `catch` methods.
- `3-all.js`: Handles multiple successful Promises using `Promise.all`.
- `4-user-promise.js`: Contains a function that returns a resolved Promise with user data.
- `5-photo-reject.js`: Contains a function that returns a rejected Promise with an error message.
- `6-final-user.js`: Handles multiple Promises and returns their statuses and values.
- `7-load_balancer.js`: Contains a function that returns the value of the fastest Promise.
- `8-try.js`: Contains a function that throws an error if division by zero is attempted.
- `9-try.js`: Contains a function that catches errors and processes them.
- `100-await.js`: Contains an `async` function that calls other `async` functions and handles their results.

## Tasks

### 0. Keep every promise you make and only make promises you can keep

Write a function `getResponseFromAPI` that returns a Promise.

### 1. Don't make a promise...if you know you can't keep it

Write a function `getFullResponseFromAPI` that takes a boolean and returns a resolved or rejected Promise.

### 2. Catch me if you can!

Write a function `handleResponseFromAPI` that handles a resolved and rejected Promise.

### 3. Handle multiple successful promises

Write a function `handleProfileSignup` that handles multiple successful Promises and logs the result.

### 4. Simple promise

Write a function `signUpUser` that returns a resolved Promise with user data.

### 5. Reject the promises

Write a function `uploadPhoto` that returns a rejected Promise with an error message.

### 6. Handle multiple promises

Write a function `handleProfileSignup` that handles multiple Promises and returns their statuses and values.

### 7. Load balancer

Write a function `loadBalancer` that returns the value of the fastest Promise.

### 8. Throw error / try catch

Write a function `divideFunction` that throws an error if division by zero is attempted.

### 9. Throw an error

Write a function `guardrail` that catches errors and processes them.

### 10. Await / Async

Write an `async` function `asyncUploadUser` that calls other `async` functions and handles their results.

## Running Tests

To run the tests for each task, use the following command:

```sh
npm run dev <task-number>-main.js
```

Example:

```sh
npm run dev 0-main.js
```

## Author

- Your Name [AbdurrahmanIdr](https://github.com/AbdurrahmanIdr)
