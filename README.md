# React Router v6 Route Params Issue

This repository demonstrates a common issue encountered when using route parameters in React Router v6. The problem occurs when a route with parameters fails to match correctly, preventing the expected component from rendering.

## Problem Description

The provided code utilizes `react-router-dom` v6. When navigating to a path containing parameters (e.g., `/users/123`), the component associated with that route does not display the expected data. This indicates a problem with either the route definition or the way parameters are handled within the component.

## Solution

The solution involves ensuring that the route parameters are correctly accessed and handled within the component. The provided solution fixes the issue by using the `useParams` hook to retrieve the parameter values from the URL.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory: `cd react-router-v6-param-issue`
3. Install dependencies: `npm install`
4. Run the application: `npm start`
5. Observe that navigating to `/users/:userId` results in an incorrect rendering.
6. Review the `bugSolution.js` file to see the fix.