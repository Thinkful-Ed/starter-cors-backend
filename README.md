# Starter: CORS Back End Application

This project provides a simple Node.js server demonstrating how to implement Cross-Origin Resource Sharing (CORS). It serves as a foundational example to help developers learn how to configure CORS for handling cross-origin requests in web applications.

## Features

- Basic Express.js setup
- Configured CORS middleware to handle requests from different origins
- Development and production mode support
- Easy to extend for adding routes and logic

## Prerequisites

To run this project, you'll need:

- [Node.js](https://nodejs.org/en/) (version 14 or higher recommended)
- [npm](https://www.npmjs.com/)

## Installation and Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Thinkful-Ed/starter-cors-backend.git
    ```
2. **Navigate into the project directory**:
    ```bash
    cd starter-cors-backend
    ```
3. **Install the required dependencies**:
    ```bash
    npm install
    ```
4. **Start the application**:
    - For a regular run:
      ```bash
      npm start
      ```
    - For development mode with auto-restart:
      ```bash
      npm run start:dev
      ```

The server will run on the default port `5555`, or you can set your preferred port by defining the `PORT` environment variable.

Example:
```bash
PORT=3000 npm start
```

## Project Structure

```bash
starter-cors-backend/
├── src/                # Contains the main application files
│   └── app.js          # Main Express application file
├── .gitignore          # Specifies files to ignore in version control
├── package.json        # Project metadata and dependencies
├── package-lock.json   # Version-lock for installed packages
└── README.md           # Project documentation
```

## How to Customize

- You can add new API routes by modifying the `src/app.js` file.
- To enable CORS for specific domains or HTTP methods, modify the CORS configuration within `app.js`.

## About CORS

CORS (Cross-Origin Resource Sharing) is a mechanism that allows web applications to securely make requests to resources on other domains. This is important for applications that communicate with APIs hosted on a different origin from the front-end application. The `cors` middleware in this project is pre-configured for ease of use.
