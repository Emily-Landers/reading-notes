# Transforms
- 2d transforms work on the x and y axis
- three dimensional transforms help define the length, width, and depth
- rotate can rotate an element 0 - 360 degrees
- the default is the center of the element 50/5/ horizontally and vertically 
- ```<figure class="box-1">Box 1</figure>```
- ```.box-1 {
  transform: rotate(20deg);
}``` 
- scale will change the appeared size of an element
- default scale is 1 
- any value between .99 and 1 will make it smaller
- 1.01 amd up will make it appear larget
- ``` <figure class="box-1">Box 1</figure> ```
- ```.box-1 {
  transform: scale(.75);
}```
- translate will push or pull an element without disrupting the natural flow of the document
- ``` <figure class="box-1">Box 1</figure> ```
- ```.box-1 {
  transform: translateX(-10px);
}```
- skew is used to distort elements on the horizontal and vertical axis
- ``` <figure class="box-1">Box 1</figure> ```
- ```.box-1 {
  transform: skewX(5deg);
}```
- multiple transformig elements can be applied at once
- transform origin is the center of an element
- the rotateX value allows you to rotate an element around the x axis, as if it were being bent in half horizontally. 
- Using the rotateY value allows you to rotate an element around the y axis, as if it were being bent in half vertically.
- using the rotateZ value allows an element to be rotated around the z axis.
# Transitions and Animations
- The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.
- There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. 
- In the example below the box will change its background color over the course of 1 second in a linear fashion.
- ```.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}```
- In the example above, the background property is identified in the transition-property value. Here the background property is the only property that will change over the duration of 1 second in a linear fashion
- The transition-timing-function property is used to set the speed in which a transition will move.
- 