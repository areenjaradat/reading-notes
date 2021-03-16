# CREATE STUNNING ANIMATED CHARTS WITH CHART.JS

best way to display data visually than table is :
Charts

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.

The < canvas> element using to create charts

canvas has two attribute with initially be 300 pixels wide and 150 pixels
and you can specify it by 2d.

## Drawing shapes with canvas

< canvas> only supports two primitive shapes: rectangles and paths

There are three functions that draw rectangles on the canvas:

fillRect(x, y, width, height)
Draws a filled rectangle.

strokeRect(x, y, width, height)
Draws a rectangular outline.

clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.

## Drawing paths

A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color.

Here are the functions used to perform these steps:

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.

## Moving the pen

moveTo(x, y)
Moves the pen to the coordinates specified by x and y.

## Lines

For drawing straight lines, use the lineTo() method.

lineTo(x, y)
Draws a line from the current drawing position to the position specified by x and y.

until now we have only seen methods of the drawing context. If we want to apply colors to a shape

## Colors

fillStyle = color
Sets the style used when filling shapes.
strokeStyle = color
Sets the style for shapes' outlines.

## Drawing text

The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.