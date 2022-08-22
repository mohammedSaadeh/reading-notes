# **Passing Functions as Props**


## What does .map() return?

-The map() method returns an entirely new array with transformed elements and the same amount of data.

## If I want to loop through an array and display each value in JSX, how do I do that in React?

-Using the map() Method

## Each list item needs a unique ____.

-Key.

## What is the purpose of a key?

-Helps React identify which items have changed, are added, or are removed.

## What is the spread operator?

-It;s a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

## List 4 things that the spread operator can do.

-Copying an array.

-Combining objects.

-Adding an item to a list.

-Using Math functions.

## Give an example of using the spread operator to combine two arrays.

-const arr1 = ["First","Second"];
 const arr2 = ["Third"];
 const arr = [...arr1,...arr2];

## Give an example of using the spread operator to add a new item to an array.

-const arr1 = ["First" ,"Second"];
 const arr2 = ["Third", ...arr1];

## Give an example of using the spread operator to combine two objects into one.

-const arr1 = {First: "1st"};
 const arr2 = {Second: "2nd"};

 const arr = {...arr1,...arr2};

 ## In the video, what is the first step that the developer does to pass functions between components?

 -Create the function wherever the state is that we are going to change.

 ## In your own words, what does the increment function do?

 -Loop through the array and when it find the match it will increase it.

 ## How can you pass a method from a parent component into a child component?

 -Like passing props.

 ## How does the child component invoke a method that was passed to it from a parent component?

 -By calling the method as a prop inside a method in the child.



 ## Things I want to know more about