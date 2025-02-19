# Unhandled Error in Asynchronous Node.js Express.js App

This repository demonstrates an example of an unhandled error in an asynchronous Node.js Express.js application and how to properly handle it.

## Bug

The `bug.js` file contains an Express.js server with a route that simulates an asynchronous operation.  If the simulated operation fails (randomly in this case), the application crashes without any proper error handling.

## Solution

The `bugSolution.js` file provides a solution by using `try...catch` blocks to handle potential errors within the asynchronous operation and sending appropriate error responses to the client.