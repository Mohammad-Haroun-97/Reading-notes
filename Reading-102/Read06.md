# CSS

***CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.***

|Objective:| 	To learn what CSS is. |
|-----------------|:-------------|
| Prerequisites: | 	Basic computer literacy, basic software installed, basic knowledge of working with files, and HTML basics (study Introduction to HTML.) |


## What is CSS for?
As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.


# Three Ways to Insert CSS
**There are three ways of inserting a style sheet:**

* External CSS
* Internal CSS
* Inline CSS
* External CSS
* With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

***Example
External styles are defined within the <link> element, inside the <head> section of an HTML page:***

<!DOCTYPE html>
<html>
<head>
<link rel="stfylesheet" href="mystyle.css">
</head>
<bodby>

<h>This is a heading</h1>
<px>This is a paragraph.</p>

</bodcy>
</html>
  
  
 ## Internal CSS  
  
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.           
  
## Inline CSS  
  
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
  
 # CSS color Property 
  Example
Set the text-color for different elements:

body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}
  
## Selectors
The following are the various selectors, which allow styles to be conditional based on various features of elements within the DOM.

## Basic selectors
Basic selectors are fundamental selectors; these are the most basic selectors that are frequently combined to create other, more complex selectors.

## Universal selector *, ns|*, *|*, |*
##Type selector elementname
##Class selector .classname
##ID selector #idname
##Attribute selector [attr=value]
##Grouping selectors
##Selector list A, B
*Specifies that both A and B elements are selected. This is a grouping method to select several matching elements.
Combinators*
***Combinators are selectors that establish a relationship between two or more simple selectors, such as "A is a child of B" or "A is adjacent to B."***

Adjacent sibling combinator A + B
Specifies that the elements selected by both A and B have the same parent and that the element selected by B immediately follows the element selected by A horizontally.
General sibling combinator A ~ B
Specifies that the elements selected by both A and B share the same parent and that the element selected by A comes before—but not necessarily immediately before—the element selected by B.
Child combinator A > B

  
  
  # Definition and Usage
The color property specifies the color of text.

Tip: Use a background color combined with a text color that makes the text easy to read.

1. Default value:	not specified
2. Inherited:	yes
3. Animatable:	yes. Read about animatable
4. Version:	CSS1
5. JavaScript syntax:	object.style.color="#0000FF"

  
  
  
  
  
  
  
  
  
  
  
  
