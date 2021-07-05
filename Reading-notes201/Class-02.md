# TEXT #

***HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
X They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).*** 

## Examples :     
  
    
1. 

```html
<blockquote>
The <blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the <p> element is still
used inside the <blockquote>
element.
```
2. 

```<strong>```
The use of the ```<strong>```
element indicates that its
content has strong importance

```html
<p><strong>Beware:</strong> Pickpockets operate in
 this area.</p>
<p>This toy has many small pieces and is <strong>not
 suitable for children under five years old.
</strong></p>
```

3.
```<hr />```
To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the ```<hr />``` tag

```html
<p>Venus is the only planet that rotates
 clockwise.</p>
<hr />
<p>Jupiter is bigger than all the other planets
 combined.</p>
```

4. 

```<br />``` 
if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag ```<br />.```

```html
<p>The Earth<br />gets one hundred tons heavier
 every day<br />due to falling space dust.</p>
 ```



# INTRODUCING CSS

* CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
* Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
* Different types of selectors allow you to target your
rules at different elements.
* Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document,
although they may appear within an HTML page.


  

  ## Examples :  

  1. 

  Using Internal CSS 
  ``` html
  <html>
<head>
 <title>Using Internal CSS</title>
 <style type="text/css">
 body {
 font-famdfmily: arial;
 backgrounud-color: rgb(185,179,175);}
 h1 {
 colodfr: rgb(255,255,255);}
 </style>
</head>
```

2.  
Using External CSS 
```css
body {
 font-fadfmily: arial;
 backgrdfound-color: rgb(185,179,175);}
h1 {
 colodr: rgb(255,255,255);}
 ```

 # Basic JavaScript Instructions
**A computer program is a list of "instructions" to be "executed" by a computer.
In a programming language, these programming instructions are called statements.
A JavaScript program is a list of programming statements.
In HTML, JavaScript programs are executed by the web browser.**

JavaScript statements are composed of:

Values, Operators, Expressions, Keywords, and Comments

### Example :
document.getElementById("demo").innerHTML = "Hello Dolly.";

# Decisions and Loops 

**A normal program is not a sequential execution of expressions or statements one after the other. It will have certain conditions to be checked or it will have certain number of iterations. When we check for certain conditions to execute further then it called as decision statements**

## If… Else Statements
These are the decision making statements.  It is used for checking certain condition to decide which block of code to be executed. The general syntax for if..else statement is as follows:

if (condition / s){
    expressions / statements;
} else {
    expressions / statements;
}

## For Loops 

**This kind of iteration to execute same set of expression/ statements is done by using FOR loops. This for loop can be used when we know the number of iterations or till it satisfies certain conditions. The general syntax for ‘For’ loop is given below :**

for (intial_value; condition; increment_factor) {
    statement/s;
  }

  ## Example :

  void main () {
  printf ("\n First 15 natural numbers are: \n");
  for (int intNum = 0; intNum < 15; intNum++) {
    printf ("%d  ", intNum);
  }
   