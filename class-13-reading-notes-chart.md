Seems straightforward enough. Download the library, or use their CDN.

Use a Canvas tag, and give it an id so we can grab onto it.

In our script tag, we need to give it a 'context' (2d/3d/whatever), and define all the data and parameters for the chart. This is really ugly and messy, I wonder if there isn't a way we could just write all of that in a separate file?

Technically, there is a way to draw text in the canvas. I don't think the canvas itself is the place to do it... but fillText and strokeText are the basic methods for accomplishing this.

Similarly, strokeStyle and fillStyle are used for colors. And if you're not drawing rectangles, you have to move a virtual pen cursor point to point.