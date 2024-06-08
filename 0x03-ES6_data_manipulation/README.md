# ES6 Data Manipulation in JavaScript

This project focuses on practicing ES6 data manipulation techniques in JavaScript. It covers various topics such as array methods (`map`, `filter`, `reduce`), typed arrays, and data structures like Set, Map, and WeakMap.

## Table of Contents

- [ES6 Data Manipulation in JavaScript](#es6-data-manipulation-in-javascript)
  - [Table of Contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Setup](#setup)
  - [Tasks](#tasks)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Contributing](#contributing)
  - [License](#license)

## Requirements

- NodeJS 12.11.x
- Jest, Babel, ESLint

## Setup

1. Install NodeJS 12.11.x:

   ```bash
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y
   ```

2. Verify NodeJS and npm versions:

   ```bash
   nodejs -v
   npm -v
   ```

3. Install Jest, Babel, and ESLint:

   In your project directory, run:

   ```bash
   npm install
   ```

## Tasks

The project consists of several tasks, each focusing on different aspects of ES6 data manipulation. Here's a brief overview:

- Basic list of objects
- More mapping
- Filter
- Reduce
- Combine
- Typed Arrays
- Set data structure
- More set data structure
- Map data structure
- More map data structure
- Weak link data structure (Advanced)

Each task has specific requirements and should be implemented in its respective file.

## Usage

To use the functions implemented in the project, import them into your JavaScript files as needed. For example:

```javascript
import getListStudents from "./0-get_list_students.js";

const students = getListStudents();
console.log(students);
```

## Testing

To test the implemented functions, run:

```bash
npm run test
```

This command will execute Jest tests to ensure that each function behaves as expected.

## Contributing

Contributions are welcome! If you find any issues or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](../LICENCE).
