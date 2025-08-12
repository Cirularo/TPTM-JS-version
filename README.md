# TPTM-JS-version
A JS version of typhoon prediction tangent maker(TPTM)

The libraries used:
proj4
paper.js

generator([[108.8, 19.0, 100], [110.4, 22.1, 170], [115.7, 26.1, 270], [120.6, 28.8, 400]])
This is a nested array containing arrays of [longitude, latitude, radius]
The whole thing is meant to be used for one single typhoon.
on a webpage, you will see two weird black lines going from top-left to bottom-right
Actually that is what is meant to be shown.
It shows two lines that work as instended.
You can use this data and generator() to generate a line and use geojson to do it.
Simply because y-coordinates on webpage increases as the page goes down, it looks like a mirrored and resized of the same line.
It's aesthetically unpleasing but it does its job at bare minimum.
Have a good day!
