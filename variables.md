# JavaScript Variables

JavaScript variables are containers for storing data values.

Before you use a variable in JavaScript, you must declare it by using the `var`keyword.

```javascript
// a, b and c are variables
var a = 2;
var b = 2;
var c = a + b;

```

#### Variable initialization
`Variable initialization` is how it is called when storing a value in a variable.

```javascript
// here we create a var named age and we assign the value 10 to it later
var age;
age = "10";

```

#### JavaScript Identifiers

All JavaScript **variables** must be **identified with unique names**.

Identifies can be short names like `a` and `b` or more descriptive names like: name, age...

There are a few rules to follow for constructing names for variables:

+ Names can contain letters, digits, underscores, and dollar signs.
+ Names must begin with a letter
+ Names can also begin with `$` and `_`
+ Names are case sensitive (`a` and `A` are different variables)
+ Reserved words (like JavaScript keywords) cannot be used as names

#### Assignment Operator
The `=` sign is an assignment operator, not *equal to*.

```javascript

x = x + 7;

```

#### JavaScript Data Types

JavaScript allows you to work with three primitive data types:

+ [`Numbers`]()
+ [`Strings`]()
+ [`Booleans`]()

Also defines two trivial data types, `null` and `undefined`, each of which defines only a single value.

A variable declared without a value will have the value `undefined`.

```javascript
// the var name will have the value undefined ofter the execution of this statement
var name;

// You can also declare multiple variables
var name = "Petal", age = "10";

// or span in multiple lines
var name = "Petal",
age = "10",
colour = "blue";

```

You can also re-declare variables:

```javascript

var name = "Petal";
var name;

// if you re-declare a variable, it will not lose its value
```

#### JavaScript Arithmetic
You can do arithmetic with JavaScript variables, using operators like `=` and `+`:

```javascript
var x = 5 + 2 + 3;

// you can also add Strings
var x = "Petal" + " " + "Maca";

```

### Next...
Go [back](https://github.com/MyPitit/JavaScript-Tutorial) or to the [next]() lesson.
