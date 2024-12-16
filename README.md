# Node.js Server Hanging on Long Requests

This repository demonstrates a common issue in Node.js where long-running operations can block the event loop, causing the server to appear unresponsive.  The `server.js` file contains the buggy code, while `serverSolution.js` shows how to fix it using asynchronous operations.