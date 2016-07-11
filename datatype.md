# JavaScript Data Types

## Primitive Data Types

|Data Type  | Description
|-----------|-------------
|String     | Represents sequence of characters e.g. "hello"
|Number     | Represents numeric values e.g. 100
|Boolean    | Represents boolean value either `false` or `true`
|Undefined  | Represents undefined value
|Null       | Represents null i.e. no value at all

In JavaScript `null` is nothing. It is supposed to be something that doesn't exists. But in JavaScript the data type of null is an object.

#### Differences between `Undefined` and `null`

```JavaScript
typeof undefined             // undefined
typeof null                  // object
null === undefined           // false
null == undefined            // true
```


## Non-primitive Data Types

|Data Type	|Description
|-----------|------------
|Object	    | Represents instance through which we can access members
|Array	    | Represents group of similar values
|RegExp	    | Represents regular expression


Examples:

```javascript
var number = 15;                                        //This is a Number
var name = "Petal";                                     //This is a String
var fruit = ["Apple", "Banana", "Orange"];              //This is an Array
var object = {firstName:"Petal", lastName:"Maca"};      //This is an Object
var person = null;                                      //The value is null, but the type is still an object
var person = undefined;                                 // Value is undefined, type is undefined

```





### Next...
Go [back]() or to the [next]() lesson.
