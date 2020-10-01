# Slide Social Buttons

Slide Social Buttons are a fun way to display your social media buttons.

The buttons are inspired by the [Supersteil blog](http://supersteil.com/blog) but instead of using jQuery for the animation, they use CSS transforms & transitions.

Feel free to [let me know](https://www.twitter.com/cmyee) if you use Slide Social Buttons in one of your websites.</p>

[View Demo](https://chrisyee.ca/slide-social-buttons)


## Features

- Uses CSS transforms & transitions.
- Uses Font Icons, perfect for retina displays.
- It's responsive!

## Requirements

- [Font Awesome 4.x](http://fortawesome.github.io/Font-Awesome/)

## Usage

Include Font Awesome and the Slide Social CSS in your header.

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css">
<link rel="stylesheet" href="path/to/your/css/slide-social-buttons.css">
```

Pick and choose which social buttons you wish to use, be sure to add the appropriate [like](https://developers.facebook.com/docs/reference/plugins/like/)/[tweet](https://twitter.com/about/resources/buttons) markup and JS as required.

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

## Thanks to

- [Supersteil](http://supersteil.com/)
- [HTML5 Boilerplate](http://html5boilerplate.com/)
- [Font Awesome](http://fontawesome.io/icons/)
