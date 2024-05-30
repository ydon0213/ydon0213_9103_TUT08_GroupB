# ydon0213_9103_TUT08_GroupB


## Instructions on how to interact with the work

The colors of the circles will update every second, creating a dynamic visual display.


## Details of my approach to animating the group code

I chose time to drive my individual code.

### Properties of the Image that will be Animated

1. Each medium circle has an array of colors that will be refreshed every second using setInterval(updateColors, 1000).
2.  Both types of circle borders (CircleBorder and CircleBorder2) and the big circles in the CirclePattern class will also have their colors updated every second.

### References to Inspiration

My inspiration comes from TeamLab, whose installations, such as those at TeamLab Borderless and TeamLab Planets in Tokyo, feature constantly changing lights and colors, creating a dynamic and immersive experience. 
[TeamLab](https://www.teamlab.art/)

### Technical Explanation

The animation effect is achieved using setInterval(updateColors, 1000), which updates colors every second. Each circle type (medium, border, and big) has an updateColors method. This method is called every second by updateColors, iterating over all instances and updating their colors. Each class has a generateColours or similar method to create arrays of random colors.

[setInterval](https://developer.mozilla.org/en-US/docs/Web/API/setInterval)