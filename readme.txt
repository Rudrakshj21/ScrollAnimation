element.getBoundingClientRect returns a DOM rect which is nothing but a rectangle (object) and this rect gives access to many properties of that element such as 
top:distance between the top of browser window and top of element
bottom: distance between top of browser window and bottom of element
x:distance between top left of element and left side / edge of browser window
y: ""        ""      "" ""   ""   ""    ""  top of browsor window

we know total height of view port is taken by window.innerHeight

so if top of box is less than innner height of window we have room for the box to be shown if not then we need to remove the boxes

[live demo at](https://rudrakshj21.github.io/ScrollAnimation/)
