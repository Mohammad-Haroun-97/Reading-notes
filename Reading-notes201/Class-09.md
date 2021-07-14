# HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

## Example
![](https://www.tutorialbrain.com/wp-content/uploads/2019/01/HTML-Form.jpg)

```html
The <form> Element
The HTML <form> element is used to create an HTML form for user input:

<form>
.
form elements
.
</form>
The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

All the different form elements are covered in this chapter: HTML Form Elements.
```

The ```<input>```Element
The HTML ```<input>``` element is the most used form element.

An ```<input>``` element can be displayed in many ways, depending on the type attribute.

Here are some examples:

Type	Description
* ```<input type="text">```	Displays a single-line text input field
* ```<input type="radio">```	Displays a radio button (for selecting one of many choices)
* ```<input type="checkbox">```Displays a checkbox (for selecting zero or more of many choices)
* ```<input type="submit">```	Displays a submit button (for submitting the form)
* ```<input type="button">```	Displays a clickable button
All the different input types are covered in this chapter: HTML Input Types.

## The ```<label>``` Element
***Notice the use of the ```<label>``` element in the example above.
The ```<label>``` tag defines a label for many form elements.
The ```<label>``` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.
The ```<label>``` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the ```<label>``` element, it toggles the radio button/checkbox.
The for attribute of the ```<label>``` tag should be equal to the id attribute of the ```<label>``` element to bind them together.***


# HTML Table   

* The ```<table>``` tag defines an HTML table.

* Each table row is defined with a```<tr>``` tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a ```<td>``` tag.

* By default, the text in ```<th>``` elements are bold and centered.

* By default, the text in```<td>``` elements are regular and left-aligned.   
Example
A simple HTML table:
```html
<table>
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


# Events 

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

HTML events are "things" that happen to HTML elements.

HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

## Example :
```
With single quotes:

<element event='some JavaScript'>
With double quotes:

<element event="some JavaScript">
```

## Common HTML Events
Here is a list of some common HTML events:

* Event	Description
* onchange	An HTML element has been changed
* onclick	The user clicks an HTML element
* onmouseover	The user moves the mouse over an HTML element
* onmouseout	The user moves the mouse away from an HTML element
* onkeydown	The user pushes a keyboard key
* onload	The browser has finished loading the page  

## What can JavaScript Do?  
  
  
Event handlers can be used to handle and verify user input, user actions, and browser actions:

* Things that should be done every time a page loads
* Things that should be done when the page is closed
* Action that should be performed when a user clicks a button
* Content that should be verified when a user inputs data
* Many different methods can be used to let JavaScript work with events:

* HTML event attributes can execute JavaScript code directly
* HTML event attributes can call JavaScript functions
* You can assign your own event handler functions to HTML elements
* You can prevent events from being sent or being handled



