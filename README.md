This repository demonstrates a common error in React applications: an infinite loop caused by an incorrectly used `useEffect` hook. The `useEffect` hook, when used without specifying a dependency array or with an incomplete dependency array, can lead to an infinite loop which causes the component to re-render repeatedly, potentially crashing the application.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version.