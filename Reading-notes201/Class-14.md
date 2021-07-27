# What Google Learned From Its Quest to Build the Perfect Team

* New research reveals surprising truths about why some work groups thrive and others falter.
Project Aristotle’s researchers began by reviewing a half-century of academic studies looking at how teams worked. 
* Were the best teams made up of people with similar interests? Or did it matter more whether everyone was motivated by the same kinds of rewards? Based on those studies, the researchers scrutinized the composition of groups inside Google: How often did teammates socialize outside the office? Did they have the same hobbies? Were their educational backgrounds similar? Was it better for all teammates to be outgoing or for all of them to be shy? They drew diagrams showing which teams had overlapping memberships and which groups had exceeded their departments’ goals.
*  They studied how long teams stuck together and if gender balance seemed to have an impact on a team’s success.

![](https://static01.nyt.com/images/2016/02/28/magazine/28mag-teams3/28mag-teams3-superJumbo.jpg?quality=90&auto=webp)

# Transforms
* With CSS3 came new ways to position and alter elements.
*  Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

* The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.


## Transform Syntax

***The value specifies the transform type followed by a specific amount inside parentheses.***

```html
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```

## 2D Transforms

* Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. 
* Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
*  Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth

## Example :     

```html
HTML
1
2
3
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>

              
CSS
1
2
3
4
5
6
7
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
  ```


  # Transitions & Animations
  * One evolution with CSS3 was the ability to write behaviors for transitions and animations.
  *  Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.

* With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

# Transitions
* an element must have a change in state, and different styles must be identified for each state.
* The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

* There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.
## Example
```html
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```


# Transitional Property
* The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. 
* By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.

* the background property is identified in the transition-property value. Here the background property is the only property that will change over the duration of 1 second in a linear fashion.
*  Any other properties included when changing an element’s state, but not included within the transition-property value, will not receive the transition behaviors as set by the transition-duration or transition-timing-function properties.

# Example : 
```
.box {
    background: #2db34a;
    border-radius: 6px
    transition-property: background, border-radius;
    transition-duration: 1s;
    transition-timing-function: linear;
  }
  .box:hover {
    background: #ff7b29;
    border-radius: 50%;
  }
  ```


  # Transitional Properties
  * background * colorbackground * positionborder-colorborder * widthborder * spacingbottomclipcolorcropfont-sizefont * weightheightleftletter * spacingline * heightmarginmax-heightmax * widthmin-heightmin-widthopacityoutline
   * coloroutline * offsetoutline * widthpaddingrighttext * indenttext 
   * shadowtopvertical * alignvisibilitywidthword-spacing


   # 6 Buttons animated
<div class="group">
		<button class="blam">Blam</button>
		<button style="-webkit-animation-delay: .3s;animation-delay: .3s;" class="syke">Syke</button>
		<button style="-webkit-animation-delay: .6s;animation-delay: .6s;" class="later">Later</button>
	</div>

    
   # CSS3 Animations: Keyframes
   <h1>CSS3 Animations: Keyframes</h1>


<div class="exampleDiv">
  <div class="ball" style="-webkit-animation: bouncing 2s 15 linear;-moz-animation: bouncing 2s 15 linear;"></div>
</div>


<!-- WhatsHelp.io widget -->
<script type="text/javascript">
    (function () {
        var options = {
            facebook: "220186546416", // Facebook page ID
            company_logo_url: "//storage.whatshelp.io/widget/d2/d2db/d2dbaa07f22d96b7ad8426beb00493d0/20031613_10154783116346417_1007255058190022230_n.png", // URL of company logo (png, jpg, gif)
            greeting_message: "Hello, how may I help you? Just send us a message now to get assistance.", // Text of greeting message
            call_to_action: "Message me", // Call to action
            position: "right", // Position may be 'right' or 'left'
        };
        var proto = document.location.protocol, host = "whatshelp.io", url = proto + "//static." + host;
        var s = document.createElement('script'); s.type = 'text/javascript'; s.async = true; s.src = url + '/widget-send-button/js/init.js';
        s.onload = function () { WhWidgetSendButton.init(host, proto, options); };
        var x = document.getElementsByTagName('script')[0]; x.parentNode.insertBefore(s, x);
    })();
</script>
   # 404

   <h1>4</h1>
<h1>0</h1>
<h1>4</h1>


  #  Pure CSS Bounce Animation
  	<div class="animation animation-1">
		<div class="ball"></div>
	</div>
	<div class="animation animation-2">
		<div class="ball"></div>
	</div>
	<div class="animation animation-3">
		<div class="ball"></div>
	</div>	