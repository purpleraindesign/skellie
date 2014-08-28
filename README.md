skellie
=======

Ellie's Infinite Scrolling Website Skeleton
===========================================

Yet another boilerplate/framewrok thingy. I started this one because I trully needed something better to work with. I like developing Infinite Scrolling websites and honestly, other frameworks like Bootstrap and Foundation added a lot of bloat into my designs and so little functionallity that I actually needed to my taste. You simply can't make those work properly when you have to add a bunch of javascript on top of it. And every other grid systems out there would miserably break when attempting fluidly control the window height.

Shorter version is I needed a sass ready framework that would fluidly control font sizes, making them proportional to the grid, not the other way around. Also, I wanted the elemets on screen to simply adapt to the window size, as opposed to creating a bunch of different layouts and hiding/showing them according to screen size. Repeating myself like that is part of the bloat caused by Bootstrap/Foundation tools that I simply wanted to get rid of.


What I'm doing then is:
=======================

1. I'm using Golden Grid System for controlling the grid and font sizes.
2. I'm using Yahoo's Pure for skinning, and making every element look pretty.
3. I'm using Font Awesome for Icon Font delight.

Golden Grid System files are fully included in the bower_components folder, although I actually re-worked the whole system by using the screen.scss file as the real grid control system.

Any adjustments and customizations can be made by changing the _settings.scss partial file. Those settings include branding, fonts, colors, etc... A bunch of customization can be done here. If that's not enough, skin it.

Skining should be made by adding your css to a new file. You can use the Skin Builder for that, as I did in the example. The Pure Skin file is named pureskellietest.scss for sass functionality embeded. I chose Pure because it is simple: one single file to add. And the Skin Builder is awesome. 

Icons also available! Using the Font Awesome package, feel free to substitute if you want.