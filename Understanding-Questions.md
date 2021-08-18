# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- dispatch passes the action object created by addOne into the reducer
- the reducer selects a case for action.type and returns a new state with the total slice of state + 1
  ...

- TotalDisplay shows the total plus 1.
