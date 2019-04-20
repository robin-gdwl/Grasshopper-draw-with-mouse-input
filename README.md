### Created by Robin Godwyll   
Robot Lab Residency Summer 2019  
BURG Halle University of Art and Design 


# Grasshopper-draw-with-mouse-input
Lets the user draw with their mouse in the Rhino viewport and converts the mouse movement into lines and points.

## How to use

Install necessary Plugins (see below).   
Download Handwriting 001.gh and drag into the Grasshopper Window

## Demo

https://youtu.be/W75_HroyJew

[![Handwriting 001 Demo](http://img.youtube.com/vi/W75_HroyJew/0.jpg)](http://www.youtube.com/watch?v=W75_HroyJew)

## Requirements:
**Software**

- Rhino 6 (using Rhino 5 will require some rewiring, use the canvas capture as a guide)
- Grasshopper 1.0.0007

**Plugins:**

- [**Interactool**](https://www.food4rhino.com/app/interactool) (required - handles the mouse tracking)
- [Metahopper](https://www.food4rhino.com/app/metahopper)(optional - only creates the sketch preview on the gh canvas)

## Overview

![Grasshopper mouse Handwriting 001 overview](https://github.com/boundlessmaking/Grasshopper-draw-with-mouse-input/blob/master/Handwriting%20001_canvas%20capture01.png?raw=true)


## Wishlist

- [ ] Make draw speed realtime
- [ ] Fix first-point-bug (first and second point are not connected)
- [ ] Increase the amount of points added per movement
- [ ] Test with touchscreen monitor
- [ ] Implement better curve interpolation 
