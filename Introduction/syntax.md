# JavaScript Syntax

JavaScript statements are separated by `semicolons`. `Semicolons` are optional, but it is a good programming practice to use `semicolons`. So please **always** use `semicolons`.

```javascript

var a = 1;
var b = 2;
var c = a + b;

```

## JavaScript Statements

#### Values
JavaScript syntax defines two values: Fixed values (`literals`) and variable values (`variables`).

+ `Literals` - Numbers are written with or without decimals

```
5.05

50

```

+ `Strings` are text, written within double or single quotes:

```
"Petal"

'Petal'

```

+ `Variables` - are used to store data values. `var` declare variables in JavaScript. Also `=` sign is used to assign values to variables.

```javascript

// a is defined as a variable, then a is assigned the value 5
var a;

a = 5;

```

#### Operators
JavaScript uses `=` to assign values to variables:

```javascript

var a = 2;

var b = 4;

```
and arithmetic operators (`+ - *  /`) to compute values:

```javascript

(2 + 2) * 5

```

#### Expressions
An expression is a combination of values, variables, and operators, which computes to a value.

Expressions can also contain variable values:

```javascript

a * 10

```

#### Keynotes
Keywords are used to identify actions to be performed. The `var` keyword tells the browser to create a new variable.

```javascript
var a = 2 + 2;

var b = a * 10;
```

#### Comments

```javascript
 // double slashes

/* between */

Comments are ignored and will not be executed.

```

#### Identifiers
Identifiers are used to name variables. In JavaScript, the first character must be a letter, `_`or `$` sign.

All `Javascript identifiers` are `case sensitive`.

```javascript
myName = "Petal";

myname = "Petal";

// myName and myname are two different variables

```
