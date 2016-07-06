#### Variable Scope
JavaScript has two `scopes`:

+ `global` - A global variable has global scope which means it can be defined anywhere in your JavaScript code
+ `local` - A `variable` that is declared inside a function definition is local.

A local variable can have the same name as a global variable, but it is entirely separate; changing the value of one variable has no effect on the other. Only the local version has meaning inside the function in which it is declared.

Example of a `Global` definition:

```javascript

var colour = " Red";

// code here can use carName

function myFunction() {

// code here can use	colour

}

```
