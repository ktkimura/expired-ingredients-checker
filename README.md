# expired-ingredients-checker
A simple microservice using a JSON file as a communication pipe. This microservice watches the JSON file for input from the main program (an array of ingredient objects) and compares the expiration dates of the ingredients against the current date. The microservice then writes an array of expired ingredient objects to the JSON file for the main program to show to the user.

## Dependencies
- Node.js
- fs
- node-watch
