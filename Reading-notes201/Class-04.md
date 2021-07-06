# Links 

***Links are created using the ```<a>``` element.
XX The ```<a>``` element uses the href attribute to indicate
the page you are linking to.
XX If you are linking to a page within your own site, it is
best to use relative links rather than qualified URLs.
XX You can create links to open email programs with an
email address in the "to" field.
XX You can use the id attribute to target elements within
a page that can be linked to.***

## Example : ##      
1.   

```html
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)
```
2.    
```html  
<p>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="about-us.html">About</a></li>
<li><a href="movies.html">Movies</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</p>
```
# LAYOUT 

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

  
  ```html
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
```

# Functions, Methods, and Objects 

## Function : 
* A JavaScript function is a block of code designed to perform a particular task.

* A JavaScript function is executed when "something" invokes it (calls it).A JavaScript function is executed when "something" invokes it (calls it).
 
* Function parameters are listed inside the parentheses () in the function definition.

* Function arguments are the values received by the function when it is invoked.

* Inside the function, the arguments (the parameters) behave as local variables.

 ## Example : 
1.  

 ```html 
 let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
```
2.  
```html
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;
```

## Methods     

JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition.
You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().

This example accesses the fullName() method of a person object:

name = person.fullName();


Using Built-In Methods
This example uses the toUpperCase() method of the String object, to convert a text to uppercase:

let message = "Hello world!";    
  

let x = message.toUpperCase();  
  

The value of x, after execution of the code above will be:

HELLO WORLD!

# Objects :  

***JavaScript Objects
You have already learned that JavaScript variables are containers for data values.

This code assigns a simple value (Fiat) to a variable named car:

let car = "Fiat";
Objects are variables too. But objects can contain many values.

This code assigns many values (Fiat, 500, white) to a variable named car:

const car = {type:"Fiat", model:"500", color:"white"};
The values are written as name:value pairs (name and value separated by a colon)***

# 6 Reasons for Pair Programming
 ## 1. Greater efficiency  
 enhances technical skills, team communication, and even enjoyability of coding in the workplace.  
   

 ##  2. Engaged collaboration   ##  
 spend no more than fifteen minutes stuck on a problem before asking a teaching assistant or instructor for help. When developers pair program, they rely more on each other and can often find a solution together without needing to ask for additional help. Ultimately, this boosts overall confidence.   


 ##  3.  Learning from fellow students    ##   
 
 The less experienced developer benefits from the experienced developer’s knowledge and guidance, and the latter benefits from explaining the topic in their own words, further solidifying their own understanding.  
   


 ## 4. Social skills   ##    

This has long-term career impacts. As much as employers want strong programmers, they know it’s essential to hire people who can work well with others.  

 ## 5. Job interview readiness  ## 
For most roles, the ability to work with and learn from others and stellar communication skills are as (or more!) important to a company than specific technical skills. Pair programming strengthens all of those skills.  
 
 ## 6.  Work environment readiness    ##
  

 Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.  





