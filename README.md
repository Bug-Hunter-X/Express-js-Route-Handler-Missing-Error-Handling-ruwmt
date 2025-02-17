# Express.js Route Handler Missing Error Handling

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when dealing with user input.

The `bug.js` file shows a route that attempts to fetch a user based on their ID. However, it doesn't handle cases where the ID is not a valid number, which can lead to errors.

The `bugSolution.js` file demonstrates how to fix this by adding error handling to check the validity of the user ID before attempting to parse it and find the user in the database.