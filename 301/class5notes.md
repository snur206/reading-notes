# [Class 5 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class4notes.md)

This topic matters because the reading continues discussing about React and a new function called Higher-Order Functions.

## React Docs - Thinking in React

Single responsibility principle is a component doing one thing.

Building a ‘static’ version of your application you are building a version that takes your data model and renders the UI but has no interactivity.

Once you have a static application, you need to Identify The Minimal (but complete) Representation Of UI State.

Three questions you can ask to determine if something is state:

- Is it passed in from a parent via props? If so, it probably isn’t state.

- Does it remain unchanged over time? If so, it probably isn’t state.

- Can you compute it based on any other state or props in your component? If so, it isn’t state.

You identify where state needs to live by identifying every component that renders something besed on that state, find a common owner component, the common component should own the state.

## Higher-Order Functions

Higer-Order functions are functions that operate on other functions, either by taking them as arguments or by returning them.







## Things I want to know more about

Higher-Order Functions
