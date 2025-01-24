# React Native useEffect Cleanup Function Error

This repository demonstrates a common error in React Native applications related to the `useEffect` hook and its cleanup function.  The issue arises when the cleanup function attempts to access or modify component state after the component has unmounted.  This often results in unexpected behavior or crashes.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.