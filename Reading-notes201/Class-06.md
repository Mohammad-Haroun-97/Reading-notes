# Object Literals

* JavaScript is case-sensitive and uses the Unicode character set. For example, the word Früh (which means "early" in German) could be used as a variable name.
* JavaScript borrows most of its syntax from Java, C, and C++, but it has also been influenced by Awk, Perl, and Python.
Objects are variables too. But objects can contain many values.

*  JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code

## Object Literal Syntax
Object literals are defined using the following syntax rules:

* colon separates property name[1] from value.
* comma separates each name-value pair from the next.
* comma after the last name-value pair is optional.[2]

## EXample : 
```html 
var Swapper = {
    // an array literal
    images: ["smile.gif", "grim.gif", "frown.gif", "bomb.gif"],
    pos: { // nested object literal
        x: 40,
        y: 300
    },
    onSwap: function() { // function
        // code here
    }
};
```
# Document Object Model
With the object model, JavaScript gets all the power it needs to create dynamic HTML:

* JavaScript can change all the HTML elements in the page
* JavaScript can change all the HTML attributes in the page
* JavaScript can change all the CSS styles in the page
* JavaScript can remove existing HTML elements and attributes
* JavaScript can add new HTML elements and attributes
* JavaScript can react to all existing HTML events in the page
* JavaScript can create new HTML events in the page

## Example : 
![DOC](https://miro.medium.com/max/461/1*XKhoU3EZcH9CrUfD5iztCw.png).  

The DOM is a W3C (World Wide Web Consortium) standard.

The DOM defines a standard for accessing documents:

"The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

The W3C DOM standard is separated into 3 different parts:

* Core DOM - standard model for all document types
* XML DOM - standard model for XML documents
* HTML DOM - standard model for HTML documents

# Understanding The Problem Domain Is The Hardest Part Of Programming
and that because :    

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

 the focus was taken off of the problem domain and put instead on the technology.

***Not only this, but as I reused this same exact application for teaching a variety of different technologies, it served as a reference problem domain that didn’t have to be re-learned, and provided a way to compare and contrast different technologies—I was getting this teaching mechanism for free if a viewer had already watched one of my other Pluralsight courses.***