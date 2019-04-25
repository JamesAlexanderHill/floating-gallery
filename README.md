# floating-gallery
## Description
This gallery displays images as if they were floating on top of the page. It has 4 layers which result in a parallax effect.
## How-To
To include this in your own website/project you can either:
* download the repo
* follow the instructions outlined below

### Instructions:
1. add css to website.
2. add a container class for the gallery to sit in as seen below:
```HTML
<div id="container">
  <div id="floatingGallery">
    <!--Images go here-->
  </div>
</div>
```
change the containers width/height to manipulate the gallery.

3. add as many images as you want

Layers - layer order is [3,2,1,0] (top->bottom)

anims - they are the same animation offset by 2 seconds. Just add the anim class randomly (anim1, anim2, anim3)

```HTML
<img class="floatingImg layer0 anim1" src="path/to/image.jpg" style="top: 5%; left: 5%;">
```
## Pull requests
Currently accepting pull requests
## Bugs
Send any bug reports you feel are necessary
