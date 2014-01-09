#Slide Social Buttons

Slide Social Buttons are a fun way to display your social media buttons. 

These buttons are inspired by the [Supersteil blog](http://supersteil.com/blog) but instead of using jQuery for the animation, they use CSS transforms &amp transitions.

Feel free to [let me know](http://www.twitter.com/cmyee) if you use Slide Social Buttons on one of your websites.

[View Demo](http://christopheryee.ca/slide-social-buttons/)

##Features

- Uses CSS transforms & transitions.
- Uses Icon Fonts, perfect for retina displays.
- Degrades gracefully for IE 8 - 9 & touch devices.
- It's responsive!

##Requirements

- [Modernizr](http://www.modernizr.com/)
- [Font Awesome](http://fortawesome.github.io/Font-Awesome/)

##Usage

Include Font Awesome, Modernizr and the Slide Social CSS in your header.

```html
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/font-awesome/3.2.0/css/font-awesome.min.css">
<link rel="stylesheet" href="path/to/your/css/slide-social-buttons.css">
<script src="//cdnjs.cloudflare.com/ajax/libs/modernizr/2.6.2/modernizr.min.js"></script>
```

Pick and choose which social buttons you wish to use, be sure to add the appropriate [like](https://developers.facebook.com/docs/reference/plugins/like/)/[tweet](https://twitter.com/about/resources/buttons)/[+1](https://developers.google.com/+/web/+1button/?hl=en) markup and JS as required.

```html
<div class="slide-social">
    <div class="button">
    	<!-- Place FB Like Button Here -->
    </div>
    <div class="facebook icon">
        <i class="icon-facebook"></i>
    </div>
    <div class="facebook slide"><p>like</p></div>
</div>
```

You can find the markup for additional social buttons in the demo file (index.html).

##Browser Compatibility

Desktop

- IE 8-9
- Chrome
- Firefox
- Safari (Mac)

Mobile

- Chrome (Android 4.2.2)
- Safari (iOS 6)

##Version History

1.0

- Inital release

##Known Issues

- IE 10 hover issues with FB Like, Twitter & Google+ buttons. Not usuable.
- iOS breaks the hover animation, the buttons will degrade gracefully for touch devices.

##Thanks to

- [Supersteil](http://supersteil.com/)
- [HTML5 Boilerplate](http://html5boilerplate.com/)
- [Modernizr](http://modernizr.com/)

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/christophery/slide-social-buttons/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
