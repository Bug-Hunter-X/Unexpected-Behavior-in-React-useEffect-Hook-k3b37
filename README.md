# React useEffect Hook Bug

This repository demonstrates a common issue with the React `useEffect` hook: incorrect usage of the dependency array.  The `useEffect` hook in `bug.js` only logs a message to the console when the `count` state variable exceeds 5. This is incorrect; it should run on every state update to display the current count. The solution, `bugSolution.js` shows the correct implementation, addressing this issue.

## Setup

Clone this repository and run `npm install` to install dependencies.  Then, run `npm start` to start the React development server.