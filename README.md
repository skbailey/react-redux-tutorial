# React/Redux Tutorial

This tutorial is from the official Redux package.

The goal is to understand how Redux manages application
state that then instructs React UI components to update

## How does Redux work?

1. An event (such as user interaction triggers) `store.dispatch()`
2. The dispatched action gets passed to a reducer
3. The reducer updates a branch of the application state
4. The updated app state passes to container components
5. Container components pass props (state/methods) to presentation components
6. Presentational components re-render with the new state

Essentially Redux is a uni-directional data store that allows devs
to reason more easily about changes to an application

## What's next

Understand optimizations and best practices that enhance this basic approach

For more info: [Redux](http://redux.js.org/index.html)