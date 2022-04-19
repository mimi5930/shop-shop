## Redux

### Three Principles

1. single source of truth: all data is stored in one spot
2. State is read-only: State cannot change
3. State is changed through pure functions: to make a change, a function must overwrite the state with a new version. Parts cannot be updated
   > Done through **_reducers_**
   > Data is **_immutable_**: never able to be directly altered

- Global state object is often referred to as a **store**

### Actions

- Define the types of events that can be emitted to update state. State can only be updated if it's a predefined action.

### Reducers

- The actual functionality that carries out the emitted action to update state

### Prop Drilling

- when state is managed at a top-level component and is passed down through too many child elements, confusing
