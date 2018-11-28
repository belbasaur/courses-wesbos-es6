# courses-wesbos-es6
Participating in ES6 for Everyone course by @wesbos

## 1 - var Scoping Refresher

### var variables 
* can be updated and redefined
* have function scope, i.e., they're only available in the function that it was created
* if not defined in a function, scope is global, i.e., window

### let and const variables
* Block scope: scoped to the block (anything between an opening and closing curly bracket)

## 2 - let VS const

### let variables
* Can only be declared once (in the same scope)
* Are made to be updated

### const variables
* Cannot be updated
* const object attributes can be updated

## 3 - let and const in the Real World

### iife (immediately-invoked function expression)
* a function that runs immediately (self invoked anonymous function)
* Prevents variables from leaking into global scope if defined within iffy

### replacing the iife
* if you declare a const inside {}, you don't have to use an iife

## 4 - Temporal dead zone
* You cannot access a variable before it is defined
* If you try to use a variable before it is defined, the variable is undefined, and doesn't give an error.
* If, however, it is e.g. a const (and not var), you would get an error instead: varname is not defined