# LAYOUT
A website is often divided into headers, menus, content and a footer:

![](https://miro.medium.com/max/1838/1*ia4V5qfk6Ki3iWIn-SmErw.png)

There are tons of different layout designs to choose from. However, the structure above, is one of the most common, and we will take a closer look at it in this tutorial.

## Header
***A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name:***
## Example :
```html
 .header {
  background-color: #F1F1F1;
  text-align: center;
  padding: 20px;
}
```
## Navigation Bar
A navigation bar contains a list of links to help visitors navigating through your website:
## Example

```html
/* Navbar links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
```
# Content
The layout in this section, often depends on the target users. The most common layout is one (or combining them) of the following:

1-column (often used for mobile browsers)
2-column (often used for tablets and laptops)
3-column layout (only used for desktops)

![](https://static.packt-cdn.com/products/9781785881008/graphics/image_04_003.jpg)

# Footer
The footer is placed at the bottom of your page. It often contains information like copyright and contact info:

## Example
```html
.footer {
  background-color: #F1F1F1;
  text-align: center;
  padding: 10px;
}
```