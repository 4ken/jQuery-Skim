jQuery Skim
====

This jQuery plugin allows you to recreate the skim effect used by Apple in iPhoto. This plugin transforms any div with an unordered list of images into a magic slideshow.

Usage
====

1. Create a `div` with the class `skim-me`: `<div class="skim-me">`
2. Use `<ul>` to wrap around your images
3. Every image is a `<li>`
4. Add at the bottom:
```javascript

 $(document).ready(function() {
        $(window).bind("load", function() {
            $(".skim-me").skim();
        });
});
```

Example
====
```html
<div class="skim-me">
    <h3>My Images</h3>
    <ul>
        <li><a href="#"><img src="images/001.jpg" width="150" height="150" alt="Image 1" /></a></li>
        <li><a href="#"><img src="images/002.jpg" width="150" height="150" alt="Image 2" /></a></li>
        <li><a href="#"><img src="images/003.jpg" width="150" height="150" alt="Image 3" /></a></li>
        <li><a href="#"><img src="images/004.jpg" width="150" height="150" alt="Image 4" /></a></li>
        <li><a href="#"><img src="images/005.jpg" width="150" height="150" alt="Image 5" /></a></li>
    </ul>
</div>
```

What's new?
====
* The first image returns after `mouseleave`.


History 
====

Forked after: https://github.com/vormplus/jQuery-Skim/issues/1
