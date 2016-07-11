# JavaScript Functions

The `Function construction`creates a new `Function object`. Every function in JavaScript is a `Function object`.

A JavaScript function is executed when something invokes it (calls it).


Example:

```javascript

function functionName(x, y) {
    return x + y;
}

// This function returns the product of x and y

```

## Function Syntax
We define a function with the keyword `function`, followed by a `name` and `()`.

Functions names can contain letters, digits, underscores, and `$` signs.

The `()` may include parameter names separated by comas like on the following example.

To execute the code, you have to place it inside `{}`.

```javascript
function name(parameter1, parameter2) {
    here you have to place the code to be executed
}
```

## Function Invocation

The code is `invoked` when:
+ A user clicks a button (`click event`)
+ It is `invoked` from JavaScript code
+ Automatically - `self invoked`

The `()` operator invokes the function.

## Function Return
When JavaScript reaches a `return statement`, the function will stop running.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The `return value` is "returned" back to the "caller":

```javascript
var x = myFunction(4, 3);        // Function is called, return value will end up in x

function myFunction(a, b) {
    return a * b;                // Function returns the product of a and b
}

// The result in x will be 12
```

You can reuse code. Defining the code once and use it as many times you need.

You can also use the same code with different arguments, to get different results.

```javascript
// The following code convert Fahrenheit to Celsius

function toCelsius(fahrenheit) {
    return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);
```

Functions can also be used as variable values in formulas, assignments, and calculations.

```javascript
//You can use:
var text = "The temperature is " + toCelsius(77) + " Celsius";

//Instead of:
var x = toCelsius(32);
var text = "The temperature is " + x + " Celsius";
```

### Next...
Go [back]() or to the [next]() lesson.
