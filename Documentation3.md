# Name: 
shapes()

## Examples:
shapes(60, 80, 0, 255);  //draw heart
shapes(mouseX, mouseY, 1, 200);  //draw star
shapes(400, 100, 2, 100);  //draw flower
  
## Description:
Miscellaneous shapes can be drawn. This function can draw stars, hearts, and flowers.

## Syntax:
shapes(x, y, typeOfShape, c)

##Parameters: 
float x: x-coordinate of the shape
float y: y-coordinate of the shape
int typeOfShape: type of shape. 0 = heart, 1 = star, 2 = flower. 
color c: the grayscale color of the shape from 0-255

##Returns:
returns void

##Other notes:
These shapes are pre-defined and cannot be changed manually.  
