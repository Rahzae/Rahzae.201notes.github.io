# Css transistion and animations
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

In the example below the box will change its background color over the course of 1 second in a linear fashion.
```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```

# Reference for simple effects
(https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

(https://codepen.io/dp_lewis/pen/gCfBv)

(https://codepen.io/akshaychauhan/pen/oAfae)

(https://codepen.io/retyui/pen/ByoaXV)
