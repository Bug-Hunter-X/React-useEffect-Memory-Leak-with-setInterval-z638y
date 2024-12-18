# React useEffect Memory Leak with setInterval

This repository demonstrates a common mistake in React's `useEffect` hook: forgetting to return a cleanup function when using `setInterval` or `setTimeout`.

This leads to memory leaks as the interval continues to run even after the component unmounts.

The `bug.js` file shows the problematic code, while `bugSolution.js` provides the correct implementation.