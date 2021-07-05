# Lists #   
  

* There are three types of HTML lists: ordered,
unordered, and definition.
* Ordered lists use numbers.
* Unordered lists use bullets.
* Definition lists are used to define terminology.
* Lists can be nested inside one another.

## Example : ## 

```html
<html>
<head>
 <title>Lists</title>
</head>
<body>
 <h1>Scrambled Eggs</h1>
 <p>Eggs are one of my favourite foods. Here is a
 recipe for deliciously rich scrambled eggs.</p>
 <h2>Ingredients</h2>
 <ul>
 <li>2 eggs</li>
 <li>1tbs butter</li>
 <li>2tbs cream</li>
 </ul>
 ```

 ## LAYOUT ##
 * ```<div>``` elements are often used as containing elements
to group together sections of a page.
* Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
* The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
* Pages can be fixed width or liquid (stretchy) layouts.
* Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page.

## Example : 
```HTML

<!DOCTYPE html
<html>
<head>
 <title>Layout</title>
 <link rel="stylesheet" type="text/css" href="css/960_12_col.css" />
 <style type="text/css">
 @font-face {
 font-family: 'QuicksandBook';
 src: url('fonts/Quicksand_Book-webfont.eot');
 src: url('fonts/Quicksand_Book-webfont.eot?#iefix') format('embedded-opentype'),
 url('fonts/Quicksand_Book-webfont.woff') format('woff'),
 url('fonts/Quicksand_Book-webfont.ttf') format('truetype'),
 url('fonts/Quicksand_Book-webfont.svg#QuicksandBook') format('svg');
 font-weight: normal;
 font-style: normal;}
 body {
 color: #ffffff;
 background: #413f3b url("images/bg.jpg");
 font-family: Georgia, "Times New Roman", Times, serif;
 font-size: 90%;
 margin: 0px;
 text-align: center;}
 a {
 color: #b5c1ad;
 text-decoration: none;}
 a:hover {
 color: #ffffff;}
 .header {
 background-image: url("images/bg-header.jpg");
 padding: 0px 0px 0px 0px;
 height: 100px;
 position: fixed;
 top: 0px;
 width: 100%;
 z-index: 50;}
 .nav {
 float: right;
 font-family: QuicksandBook, Helvetica, Arial, sans-serif;
 ```

 # JavaScript Basics # 

 1. ## CHANGING THE VALUE OF A VARIABLE ##  

 Once the variable has been created, you do not need to use the var keyword to assign it a new value. You just use the variable name, the equals sign (also known as the assignment operator), and the new value for that attribute.  
## Example : ## 
```
inStock = false;
shipping = true;
var elStock = document.getElementByld('stock');
elStock .className = inStock;
var elShip = document .getElementByld('shipping');
elShip .className = shipping;
```

2. ## USING A VARIABLE TO STORE A BOOLEAN ## 

Because strings can live in single or double quotes, if you just want to use double quotes in the string, you could surround the entire string in single quotes You can also use a technique called escaping the quotation characters. This is done by using a backwards slash

## Example : ##
```html
var title;
var message;
c02/ js/string-with-quotes.js
title= "Molly's Special Offers" ;
message = '<a href=\"sale .html\">25% offl</a>' ;
var elTitle = document.getElementByld('title') ;
elTitle.innerHTML =title;
var elNote = document.getElementByid ('note') ;
elNote.innerHTML =message; 
```

# Decisions and Loops # 

This is how it works:

* The switch expression is evaluated once.
* The value of the expression is compared with the values of each case.
* If there is a match, the associated block of code is executed.
* If there is no match, the default code block is executed.

## Example : ## 
```html
switch (new Date().getDay()) {
  case 6:
    text = "Today is Saturday";
    break;
  case 0:
    text = "Today is Sunday";
    break;
  default:
    text = "Looking forward to the Weekend";
}
```



