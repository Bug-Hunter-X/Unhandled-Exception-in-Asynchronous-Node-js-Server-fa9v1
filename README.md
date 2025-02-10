# Unhandled Exception in Asynchronous Node.js Server

This repository demonstrates a common error in Node.js applications: unhandled exceptions in asynchronous operations.  The `bug.js` file shows a server that might throw an error during an asynchronous task, causing the server to crash.  The solution in `bugSolution.js` addresses this by implementing proper error handling using try...catch blocks and ensuring all asynchronous operations are handled gracefully.