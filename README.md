learning process for React redux tool kit From https://newline.com
# installation process
 - npm install 
 - npm start

# Redux Toolkit:
redux toolkit for creating and managing redux applications written in React 
- use for managing states of the applications
- keeping all the components in sync
- Centralizing application state 
- having single source of truth
- Avoid Props drilling

# Fundamentals of Redux
- The global state of the application is stored in an object within a single store
- State is ready only , so we cannot use store.user = {name.Chirag}
- To update Store, we need a function which takes store as a parameter and returns an updated one (Reducer)

# Building Blocks

* Action -->dispatch--- > * Store----> Reducer

# Redux Toolkit - slice


# pros & cons 
- easy to debug
- Avoids props drilling
- single source of truth
* / cons :
-little complex if not familiar with functional paradigm


# Store
- A store is a container that holds the Application state 
- it's plain javascript object that can be used to store state information
- single source of truth can be used to store state information
- Also known as Front End Database
- Can be accessed from the application
 
# Stacks Used:
- react
- Redux-Toolkit
- npm
- css