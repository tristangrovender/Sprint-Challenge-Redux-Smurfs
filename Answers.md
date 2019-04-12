1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?

-Map, reduce, and filter.
-Object.assign is what we use to accomplish this task 

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

-Actions are to a reducer then the reducer does something to the state, the store is where all state is held.

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?


1.  What is middleware?

Middleware takes and action and manipulates it before sending it on to the reducer.

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

This allows us to run asynchronous JS.

1.  Which `react-redux` method links up our `components` with our `redux store`?

connect
