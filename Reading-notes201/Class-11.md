# Images

The HTML ```<img>```< tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The ```<<img>```< tag creates a holding space for the referenced image.

The ```<<img>```< tag is empty, it contains attributes only, and does not have a closing tag.

The ```<<img>```< tag has two required attributes:

 * src - Specifies the path to the image
* alt - Specifies an alternate text for the image

## The src Attribute
***The required src attribute specifies the path (URL) to the image.
Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.***

## Example
```html <img src="img_chania.jpg" alt="Flowers in Chania">```

## Example
```html <img src="img_girl.jpg" alt="Girl in a jacket">```

## The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

## Example
```<img src="img_chania.jpg" alt="Flowers in Chania">```

# Width and Height, or Style?
**The width, height, and style attributes are all valid in HTML.
However, we suggest using the style attribute. It prevents styles sheets from changing the size of images:**
```
Example
<!DOCTYPE html>
<html>
<head>
<style>
img {
  width: 100%;
}
</style>
</head>
<body>

<img src="html5.gif" alt="HTML5 Icon" width="128" height="128">

<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

</body>
</html>
```

## Image Floating
Use the CSS float property to let the image float to the right or to the left of a text:

## Example
```html
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>

```

# Practical Information 
* Search engine optimization helps visitors find your
sites when using search engines.
*  Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.
*  To put your site on the web, you will need to obtain a
domain name and web hosting.
*  FTP programs allow you to transfer files from your
local computer to your web server.
*  Many companies provide platforms for blogging, email
newsletters, e-commerce and other popular website
tools (to save you writing them from scratch


# HTML5 video and audio

***The ```<video>```and ```<<audio>```< elements allow us to embed video and audio into web pages. As we showed in Video and audio content, a typical implementation looks like this:***

```html
<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```