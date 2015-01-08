#Slide Social Buttons

Slide Social Buttons are a fun way to display your social media buttons.

The buttons are inspired by the [Supersteil blog](http://supersteil.com/blog) but instead of using jQuery for the animation, they use CSS transforms & transitions.

As of version 2.0, they're only compatible with CSS3-compliant browsers. This mainly means <strong>no IE 8</strong>. If you still need IE8 compatibility, version 1.0 will always be available.

Feel free to let [the original creator](http://www.twitter.com/cmyee) know if you use Slide Social Buttons in one of your websites.</p>

View Demo: [v 1.0](http://christopheryee.ca/slide-social-buttons/) | [v 2.0](http://shared.bhstudios.org/_plug/slide-social-buttons/)

##Features

- Uses CSS transforms & transitions.
- Uses Font Icons, perfect for retina displays.
- It's responsive!

##Requirements

- [Modernizr](http://www.modernizr.com/)
- [Font Awesome 4.x](http://fortawesome.github.io/Font-Awesome/)

##Usage

Include Font Awesome and the Slide Social CSS in your header.

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css">
<link rel="stylesheet" href="path/to/your/css/slide-social-buttons.css">
```

Pick and choose which social buttons you wish to use, be sure to add the appropriate [like](https://developers.facebook.com/docs/reference/plugins/like/)/[tweet](https://twitter.com/about/resources/buttons)/[+1](https://developers.google.com/+/web/+1button/?hl=en) markup and JS as required.

```html
<div class="slide-social">
    <div class="ss-button">
    	<!-- Place FB Like Button Here -->
    </div>
    <div class="facebook-bg ss-icon">
        <i class="fa fa-facebook"></i>
    </div>
    <div class="facebook-bg ss-slide"><p>like</p></div>
</div>
```

You can find the markup for additional social buttons in the demo file (index.html).

##Browser Compatibility

- Any evergreen browser <sub>([What's that?](http://eisenbergeffect.bluespire.com/evergreen-browsers/))</sub>

##Version History

2.0 (2015-01-04)

	! Blue Husky Studios refined it to work better as a plugin to an existing site.
		- REMOVED IE8 COMPATIBILITY - now designed for evergreen browsers.
		+ Created branding (icon and logo), added in ./branding/
		! Updated Font Awesome requirement to 4.x
		! Removed requirement for Modernizr.js
		+ Added .tumblr-bg
		! Removed need for .ss-slide p element
		- Removed rule that never showed Twitter backup "Tweet" link
		! Implemented calc() positioning when possible
		. Changed px to em where possible
		. Moved white line from left of .ss-slide p to right of .ss-icon
		! Implemented absolute positioning on .ss-slide instead of float
		. Changed .ss-button positioning from pixels to percents
		. Changed .ss-button positioning from margin-based to top- and left- based
		. Reformatted documentation to fit Blue Husky standards
		+ Added the 'ss-' prefix to any generic class name
		! Made .slide-social relative so internal buttons don't align with another positioned ancestor
		! Gave .ss-slide a 2-second return delay so button is still uncovered when clicking in IE.

1.0

- Inital release

##Known Issues

- IE 10 hover issues with FB Like, Twitter & Google+ buttons. Not usuable.
- iOS breaks the hover animation, the buttons will degrade gracefully for touch devices.

##Thanks to

- [Supersteil](http://supersteil.com/)
- [HTML5 Boilerplate](http://html5boilerplate.com/)
- [Christopher Yee](http://christopheryee.ca/)

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/christophery/slide-social-buttons/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
