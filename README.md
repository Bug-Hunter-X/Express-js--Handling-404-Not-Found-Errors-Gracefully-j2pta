# Express.js 404 Not Found Error Handling

This repository demonstrates a common issue in Express.js applications: inconsistent handling of 404 (Not Found) errors.  The `bug.js` file showcases a scenario where an incomplete 404 response can lead to problems. The `bugSolution.js` file provides a corrected approach that is more robust and consistent. 

## Problem

In the buggy code, if a user is not found, the server sends an error with a correct status code (404). However, a better solution is to send a JSON response explicitly stating that the user was not found, which is easier for clients to understand.