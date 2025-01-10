# Node.js Server Error Handling

This repository demonstrates a common error in Node.js applications: lack of proper error handling. The initial `server.js` file showcases a server susceptible to crashes due to unhandled exceptions. The improved `serverSolution.js` file demonstrates how to add robust error handling to prevent unexpected server downtime. 

## Problem

The original server lacks any mechanisms to catch or log errors.  This makes it vulnerable to crashes if an unexpected error occurs during request processing.

## Solution

The improved solution uses `try...catch` blocks to handle potential errors.  Additionally, error details are logged to the console to aid in debugging.  A more sophisticated approach might include logging to a centralized system and implementing error monitoring tools. 