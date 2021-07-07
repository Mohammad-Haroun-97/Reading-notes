# Images #      

* The ```<img>``` element is used to add images to a
web page.
* You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
* You should save images at the size you will be using
them on the web page and in the appropriate format.
* Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.

## Example : 
```html
<body>
<h1>
<img src="images/logo.gif"
alt="From A to Zucchini" />
</h1>
<figure>
<img src="images/chocolate-islands.jpg"
alt="Chocolate Islands"
title="Chocolate Islands Individual Cakes" />
<p>
<figcaption>
This recipe for individual chocolate
cakes is so simple and so delectable!
</figcaption>
</p>
</figure>
<h4>More Recipes:</h4>
<p>
<img src="images/lemon-posset.jpg"
alt="Lemon Posset"
title="Lemon Posset Dessert" />
<img src="images/roasted-brussel-sprouts.jpg"
alt="Roasted Brussel Sprouts"
title="Roasted Brussel Sprouts Side Dish" />
<img src="images/zucchini-cake.jpg"
alt="Zucchini Cake"
title="Zucchini Cake No Frosting" />
</p>
</body>
</html>
```

# Colors : 

* Color not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.

## Example :  
```html
<!DOCTYPE html>
<html>
<head>
<title>Color</title>
<style type="text/css">
body {
background-color: silver;
color: white;
padding: 20px;
font-family: Arial, Verdana, sans-serif;}
h1 {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);
color: #64645A;
padding: inherit;}
p {
padding: 5px;
margin: 0px;}
p.zero {
background-color: rgb(238,62,128);}
p.one {
background-color: rgb(244,90,139);}
p.two {
background-color: rgb(243,106,152);}
p.three {
background-color: rgb(244,123,166);}
```

# TEXT

* There are properties to control the choice of font, size,
weight, style, and spacing.
* There is a limited choice of fonts that you can assume
most people will have installed.
* If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
* You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
* You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.

## Example : 
```html 
<body>
<h1>Briards</h1>
<h2>A Heart wrapped in fur</h2>
<p class="intro">The <a class="breed" href="http://en.wikipedia.org/wikiBriard">
briard</a>, or berger de brie, is a large breed of dog traditionally used as a
herder and guardian of sheep.</p>
<h3>Breed History</h3>
<p>The briard, which is believed to have originated in France, has been bred for
centuries to herd and to protect sheep. The breed was used by the French Army as
sentries, messengers and to search for wounded soldiers because of its fine sense
of hearing. Briards were used in the First World War almost to the point of
extinction. Currently the population of briards is slowly recovering.
Charlemagne, Napoleon, Thomas Jefferson and Lafayette all owned briards.</p>
<p class="credits">by Ivy Duckett</p>
</body>
</html>
```

# JPEG vs PNG vs GIF — which image format to use and when?

***3 image formats have significant differences amongst themselves thus making each of them suitable for specific use cases. Understanding these major differences would help us deliver the best possible images to our website and mobile app users.***

## TL;DR
***Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.***

## Compression
***Almost all forms of data that we see on the internet — text, image, video etc. — are compressed to reduce the size of data and ensure faster transmission.***

## JPEG 
***is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality.***