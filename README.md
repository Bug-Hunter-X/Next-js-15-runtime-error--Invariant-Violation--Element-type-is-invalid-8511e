# Next.js 15 Runtime Error: Invariant Violation

This repository demonstrates a common runtime error in Next.js 15 applications and its solution.  The error occurs when an incorrectly defined or exported component is rendered.  Specifically, it highlights the "Invariant Violation: Element type is invalid" error.

## Problem

The `pages/index.js` file attempts to render a component called `MyComponent`, but there's an issue with how it's defined or exported, leading to the runtime error.

## Solution

The solution involves correctly defining and exporting the `MyComponent` component.  The key is ensuring the component is properly exported from its containing file (in this case, `pages/index.js`).

## Reproduction

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the Next.js development server.
4. Observe the runtime error in the browser console.

After applying the fix in `bugSolution.js`, rerun the development server to see the error resolved.
