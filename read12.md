# Read: 12 - Docs for the HTML <canvas> Element & Chart.js

Setting up chart 
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script

Drawing a _line chart_ by canvas element .

Drawing a _pie chart_ by Chart().pie(): we just need to supply a value and a color for each section

Drawing a _bar chart_ by Chart().Bar();


<canvas> element has only two attributes, width and height.

 <canvas> element requires the closing tag (</canvas>).

 <canvas> only supports two primitive shapes: rectangles and paths 


1. Draws a filled rectangle.:  fillRect(x, y, width, height) to style it fillStyle = color .
2. Draws a rectangular outline.: strokeRect(x, y, width, height) to style it  strokeStyle = color .
3. Clears the specified rectangular area, making it fully transparent.:clearRect(x, y, width, height)

