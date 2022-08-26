# **Putting it all together**


## What is the single responsibility principle and how does it apply to components?

-a component should only do one thing and each component should have a single responsibility.

## What does it mean to build a ‘static’ version of your application?

-It shows you the UI but has no interactivity.

## Once you have a static application, what do you need to add?

-Functionality by passing state.

## What are the three questions you can ask to determine if something is state?

-Is it passed in from a parent via props? If so, it probably isn’t state.

-Does it remain unchanged over time? If so, it probably isn’t state.

-Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

-Identify every component that renders something based on that state.

-Find a common owner component (a single component above all the components that need the state in the hierarchy).

-Either the common owner or another component higher up in the hierarchy should own the state.

-If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## What is a “higher-order function”?

-Functions that operate on other functions, either by taking them as arguments or by returning them.

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

-It returns a function (m) which returns (m>n).

## Explain how either map or reduce operates, with regards to higher-order functions.

-Map goes through an array and take a call back function as an argument. It returns a new array without modifying the original array.


## Things I want to know more about