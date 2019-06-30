# Introduction
## CSS
Get started with Bootstrap, the world’s most popular framework for building responsive, mobile-first sites, with BootstrapCDN.

 - Copy-paste the stylesheet ```<link>``` into your ```<head>``` before all other stylesheets to load Bootstrap CSS.
 
> ```<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">```
 
# JS
 - Many of Bootstrap components require the use of JavaScript to function.
 - Specifically, they require jQuery, Popper.js, and Bootstrap JavaScript plugins.
 - Place the following `<script>`s near the end of your pages, right before the closing `</body>` tag, to enable them.
 ```
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
 ```
 - jQuery must come first, then Popper.js, and then Bootstrap JavaScript plugins.
 - Bootstrap use jQuery’s slim build, but the full version is also supported.
 > ## Note:
 > `bootstrap.bundle.js` and `bootstrap.bundle.min.js` include Popper, but not jQuery.
 
# Important globals
  - Bootstrap employs a handful of important global styles and settings that you’ll need to be aware of when using it
  - All of which are almost exclusively geared towards the normalization of cross browser styles. Let’s dive in.
# HTML5 doctype
  - Bootstrap requires the use of the HTML5 doctype.
  - Without it, you’ll see some funky incomplete styling, but including it shouldn’t cause any considerable hiccups.
