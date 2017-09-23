A super simple accordion that is CSS only. Easily adaptable to fit any needs.


# How it works

The accordion uses `input[type=checkbox]:checked` to toggle the next div as visible or hidden. It can be adapted any which way or styled hover you want, as long as you follow a very simple class structure.

Wrap everything in an ".accordion" class. Each accordion section needs to be wrapped in a ".accordion-section" to control it. The next item needs to be the input checkbox with the ".accordion-toggle" class. After that, use a ".accordion-content" class on a div to wrap the content. Inside that div, you can put whatever you want.

Use the "checked" setting on the input to hide the content, remove it to show it.

It also has a simple CSS animation for the show/hide.


## Compatibility

The transform property is not supported on IE8. 



## My Super Simple Series

The goal of the Super Simple Series is to have code as slim as possible to accomplish a goal, yet still be adaptable enough to be actually useful in a real project.

Have I met this goal? Who knows.
