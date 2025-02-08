# React Router DOM v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router DOM v6.  The catch-all route is intended to handle any unmatched routes and display a 404 page (Not Found), but in this example, it fails to work correctly.

## Problem Description

The provided `App.js` demonstrates a simple React application using React Router v6. Despite having a catch-all route (`/*`) for handling 404 errors, unmatched routes incorrectly display the Home component. This indicates that the catch-all route is not functioning correctly.

## Solution

The solution is provided in `AppSolution.js`. It highlights the correct implementation of the catch-all route within the Routes component.

## How to reproduce

1. Clone this repository.
2. Navigate to the directory in your terminal.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Navigate to any invalid route (e.g., `/invalid-route`).
6. Observe that the Home component is rendered instead of the NotFound component in the original App.js.  The corrected behavior will be seen in AppSolution.js
