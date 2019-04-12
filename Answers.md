1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?

-Map, reduce, and filter.
-Object.assign is what we use to accomplish this task 

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

-Actions go to a reducer then the reducer does something to the state, the store is where all state is held.

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?

- Application state can be accessed by all components where as component state cannot. If you only need to use state within 1 component then component state is a good choice, app state is a good choice if multiple components might need that state.

1.  What is middleware?

-Middleware takes an action and manipulates it before sending it on to the reducer.

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

-Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods dispatch and getState as parameters.

1.  Which `react-redux` method links up our `components` with our `redux store`?

connect
