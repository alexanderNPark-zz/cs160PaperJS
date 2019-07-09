Implement a gradient fill tool
Using the Paper.js library, draw a red rectangle at a hard-coded location at the center of the screen. Place the rectangle over the mandala, there’s no need to remove the mandala first (the mandala is just there to show you how to add an outline to the page for your interactive coloring prototype after this implementation prototype). Fill the rectangle with red color.
Then, create a paper.Tool with the following behavior. When the mouse is released over the rectangle (i.e. on a mouse-up event), the fill color (fillColor) of the rectangle should be set to a gradient color. 
The origin for the gradient should be the mouse-down location, and the destination of the gradient should be the mouse-up location. The stops should be the last two colors selected from the color palette (which should be stored in cp.history).
You must implement this rectangle gradient interaction. In the index.html file (under the folder coloring/templates/coloring/), this logic should be written in the myGradientInteraction function. You should change no more than around 20-30 lines of code in the starter project.
Use codeanywhere container set port 8000. 
