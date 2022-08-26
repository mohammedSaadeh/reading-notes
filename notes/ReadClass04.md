# **React and Forms**


## What is a ‘Controlled Component’?

-Controlled Components are those in which form's data is handled by the component's state. 

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

-We should update the state with their responses as soon as they enter them. because changing the input will update the state, and updating the state will change the input.

## How do we target what the user is entering if we have an event handler on an input field?

-By add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## Why would we use a ternary operator?

-To make the if else statment shorter.

## Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

-(x==y)? console.log(true) : console.log(false) ;




## Things I want to know more about