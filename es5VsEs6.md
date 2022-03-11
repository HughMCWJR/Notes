# ES5 vs ES6

## Variables
- ES5 only has **var**
- ES6 has **let** and **const**

## Object definition
- ES6 has shorthand for defining an object where the key and variable names are the same
```
var fullName = 'John Moore';
var age = 25;
var gender = 'Male';
var city = 'London'
// ES5
var student = { fullName: fullName, age: age, gender: gender, city: city };
// ES6
var student = { fullName, age, gender, city };
```

## Merge Objects
- Use spread operator (**...**) to get all items in object for merging
```
var target = { firstName: 'John', age: 25 }
var source = { fullName: 'John Moore', gender: 'Male', city: 'London' }
//ES5
var updatedTarget = Object.assign(target, source); //changes the target variable
//ES6
var updatedTarget = { ...target, ...source};
```

## Object Destructuring
- ES6 introduced this syntax:
```
let o = {
    a: "foo",
    b: 12,
    c: "bar",
};
```
- To get **a** and **b**:
```
let { a, b } = 0;
```

## String Interpolation
- Can add string variables inside larger string with **${var}**

## Promises
- ES6 introduced promises