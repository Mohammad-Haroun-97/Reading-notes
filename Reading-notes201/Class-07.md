
# Domain Modeling
***A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.***


## Define a constructor and initialize properties

To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.


| Property |Data | Type  | 
|-----------------|:-------------|:---------------:|
| epicRating | 1 to 10  | Number      | 
| hasAnimals     | true or false          | Boolean      | 


Example: 
```html 
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
```
## Generate random numbers
## Example :
```html 
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

EpicFailVideo.prototype.generateRandom = function(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail.generateRandom(1, 5));
console.log(corgiFail.generateRandom(1, 5));

```

# Tables
The ```<table>``` tag defines an HTML table.

Each table row is defined with a ```<tr> ```tag. Each table header is defined with a``` <th>``` tag. Each table data/cell is defined with a ```<td>``` tag.

By default, the text in ```<th> ```elements are bold and centered.

By default, the text in```<td> ```elements are regular and left-aligned.

## Example
A simple HTML table:
```html
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

# Functions, Methods, and Objects

The this Keyword     

* In a function definition, this refers to the "owner" of the function.

* In the example above, this is the person object that "owns" the fullName function.

* In other words, this.firstName means the firstName property of this object.

* Read more about the this keyword at JS this Keyword.

## JavaScript Methods
JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition.

## Example : 
```
person.name = function () {
  return this.firstName + " " + this.lastName;
};
```

# Objects 
* Objects are variables too. But objects can contain many values.
* You define (and create) a JavaScript object with an object literal
* Objects can also have methods.

* Methods are actions that can be performed on objects.

* Methods are stored in properties as function definitions.

Example : 
```html
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```