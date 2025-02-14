# Next.js 15 App Router Unexpected Error with Simple Functional Component

This repository demonstrates a bug in Next.js 15's App Router where a simple functional component throws an unexpected error.  The error occurs despite the component seemingly being correctly implemented.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the error in the terminal and the blank page in the browser.

## Expected Behavior

The application should render 'Hello world' without any errors.

## Actual Behavior

An unexpected error is thrown, preventing the component from rendering.

## Solution

The solution involves ensuring that the component is exported correctly, and that there are no issues with the project configuration that might be causing the unexpected behavior.  See `bugSolution.js` for a corrected version.