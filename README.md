# Firebase Optimistic Update Race Condition
This repository demonstrates a race condition that can occur when using optimistic updates in Firebase. The client reads data, modifies it, and updates the server.  However, if the server's data changes in the meantime, a conflict arises. This can lead to incorrect data display on the client-side.

The `bug.js` file shows the problematic code, and `bugSolution.js` provides a solution using appropriate data synchronization techniques and conflict resolution.