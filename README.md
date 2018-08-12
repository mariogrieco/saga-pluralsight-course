
# What is redux-saga '?'

- redux middleware process manager.
- consumes/listen actions, dispatch actions and side-effects (using effects).
- mantains runing process called sagas.

# What is a saga '?'

- in functional programing is for reset series of reversible transactions.
- in redux manage complex side-effecs or async logics using a background long-process, and yield es6.

--- Keywords ---

- Effect:
  Effects are simple JavaScript objects which contain instructions to be
  fulfilled by the middleware. When a middleware retrieves an 
  Effect yielded by a Saga, the Saga is paused 
  until the Effect is fulfilled.
  You can view Effects like instructions to the middleware to 
  perform some operation (e.g., invoke some asynchronous function, 
  dispatch an action to the store, etc.).
  -- redux-saga/effects..
  cps 
  call
  https://redux-saga.js.org/docs/api/

- Saga Helpers:
    some helpers Effects...
    takeEvery, takeLatest

- Declarative Effects:

- Dispatching actions to the store
