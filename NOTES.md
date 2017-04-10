## Actions
  - Payloads of information that data from the application to the store
    - The _only_ source of information for the store
  - Send actions via `store.dispatch()`

  ```js
  const ADD_TODO = 'ADD_TODO';

  {
    type: ADD_TODO,
    text: 'Build my first redux app',
  }
  ```
  - Plain js objects
    - PASS AS LITTLE DATA IN THE OBJ AS POSSIBLE
  - Must have a `type` property, indicating the type of action to performs
  - Good idea: add unique ID (an index value) with each action

## Reducers
  - Tie state and action together

## Store

## Data Flow

## Usage with React
