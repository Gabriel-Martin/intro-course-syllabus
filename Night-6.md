# Night 6: JS Fundamentals & DOM

## Review:

- JS Types:
  _ String
  _ Number
  _ Boolean
  _ Array
  _ Object
  _ Variables

## Functions:

A function is a block of code that performs a specific task.  
The code inside the function doesn’t run until that function is called/invoked.

Example:

```javascript
var newFunction() {
	console.log(“Hello Functions!”);
};

newFunction();
```

## Parameters and Arguments:

Parameters:  
A parameter is a value that is listed inside the function parentheses, and referenced from inside the function body.

Example:

```javascript
var greeting(greet) {
	console.log(greet);
};
```

Arguments:  
Arguments are values passed into the function parentheses when that function is called/invoked.

Example:

```javascript
greeting(“Welcome to params & args!”);
```

## DOM Manipulation:

DOM stands for Document Object Model.  
 The DOM holds references to our HTML elements and allows us to manipulate those elements from within Javascript.  
 We treat the dom like a javascript object, referencing it with the keyword document.

- Key concepts:
  _ Get element by Id
  _ Set inner text | inner HTML of an element
  _ Set element class
  _ Creating new elements \* Appending child elements to parent

### Class Project:

Instructor lead examples of the key concepts of DOM manipulation.
