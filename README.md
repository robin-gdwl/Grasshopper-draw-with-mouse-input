### Created by Robin Godwyll   
Robot Lab Residency Summer 2019  
BURG Halle University of Art and Design


# Grasshopper-draw-with-mouse-input
Lets the user draw with their mouse in the Rhino viewport and converts the mouse movement into lines and points.

After finishing this definition I found an easier one that does something very similar by utilising the `sketch`command in Rhino and then importing the Curves with the geometry pipeline. Its made by [Dan Taeyoung](https://github.com/dantaeyoung) You can find [it here](https://github.com/dantaeyoung/GrasshopperArsenal/tree/master/SketchGestures). Try it out if it suits you better than this one.

## Demo

<img src="/Images/GH-draw-demo_01.gif" width="50%">

https://youtu.be/W75_HroyJew

[![Handwriting 001 Demo](http://img.youtube.com/vi/W75_HroyJew/0.jpg)](http://www.youtube.com/watch?v=W75_HroyJew)

## How to use

Install necessary Plugins (see below).   
Download the file **`GH_Draw-with-mouse-input v_X.X.X.gh`** and drag into the Grasshopper Window

## Requirements:
**Software**

- Rhino 6 (using Rhino 5 will require some rewiring, use the canvas capture as a guide)
- Grasshopper 1.0.0007

**Plugins:**

- [**Interactool**](https://www.food4rhino.com/app/interactool) (required - handles the mouse tracking)
- [Metahopper](https://www.food4rhino.com/app/metahopper)(optional - only creates the sketch preview on the gh canvas)

## Overview

![Grasshopper mouse Handwriting 001 overview](https://raw.githubusercontent.com/boundlessmaking/Grasshopper-draw-with-mouse-input/master/GH_Draw-with-mouse-input%20v_1.0.1_Canvas_alpha.png)


## Wishlist

- [ ] Make draw speed realtime
- [x] Fix first-point-bug (first and second point are not connected)
- [ ] Increase the amount of points added per movement
- [ ] Test with touchscreen monitor
- [ ] Implement better curve interpolation
