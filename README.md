# ZoomNPan
Use mouse wheel to zoom an image and move the mouse to pan around. Just using vanilla javascript in 50 lines.

Live example:
http://jsfiddle.net/Victornpb/1s3nm8h8/

Usage
----

Works on any div that have a background image

HTML
```
<div id="myDiv" style="background: url('cat.jpg')"></div>
```

Javascript
```
var zp = new ZoomNPan(myDiv); //That's it!
```
# API

## Properties

- minimum zoom allowed (in percent)  
    `ZoomNPan.minScale = 30;`
    
 - maximun zoom allowed (in percent)  
   `ZoomNPan.maxScale = 300;`
    
 - Snap to 100% if the zoom is in +- this amount (in percent)  
    `ZoomNPan.snap = 9;`
    
 - invert the direction on MacOS  
    `ZoomNPan.invertOnMac = false;`
    
    
## Methods
    
 - theardown the events and remove styles, call this when you don't need it anymore.   
    `ZoomNPan.destroy()`
    
-----

## Suggestions / Questions

File a [issue](https://github.com/victornpb/ZoomNPan/issues) on this repository.
