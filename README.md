Pic Reshape Editor JS (Drop, Crop and Resize Image)
===================================================

A Pic Reshape that makes it easy to upload, drag & drop, crop and resize image on clinet side. You can also set the ideal dimensions for your images.

Although basic functionality like this is easy to write, it can quickly get complex in certain situations.. 

### [View Demo](http://developers.rohitiuc.info/pic-reshape.html)

Basic usage
-----------
__Note:__ These apply all elements inside targeting element.


```html
<div class="pic-block" data-crop=">=200,>=200">
    <div class="drop-description">Drag & Drop here...</div>
    <img />
    <input type="file"/>
</div>
```

 
Options
-------

This will use the data attribute name `data-crop`. This attribute receives the minimum and maximum dimensions for the width and height of the cropped image.