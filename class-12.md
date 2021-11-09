# Chart.js
- all that is needed is the script included in your page along with a single ```<canvas>``` node to render the chart 
- use the MIT license for chart.js
- line charts start with ```<canvas id="buyers" width="600" height="400"></canvas>```
- pie charts start with ```<canvas id="countries" width="600" height="400"></canvas>```
- bar charts start with ```<canvas id="income" width="600" height="400"></canvas>```
- ```<canvas>``` is similar to the  ```<img>``` element, with the main difference being that it doesn't have the src and alt attributes
- ```<canvas>``` requires a closing tag
- ``` getContext()``` is used to obtain the rendering context and its drawing functions
- canvas can be used to create many different shapes
- ```fillStyle = color```Sets the style used when filling shapes.
- ```strokeStyle = color``` Sets the style for shapes' outlines.
- ```fillText(text, x, y [, maxWidth])``` Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- ```strokeText(text, x, y [, maxWidth])``` Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

