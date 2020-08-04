YES. Design is one thing, code is another. When coding a site from a wireframe or design...

Whole to the specific - start big and work your way down. Find the big things, then break them into increasingly smaller boxes. Split the page design into large sections; divide large sections into smaller parts - look for sections that are repeated frequently; make the parts even smaller.

Apparently, our file structure should emulate the visual design breakdown - big things, smaller things, atomic things, etc. When actually building things with code, instead of visually starting big and breaking things down, start at the smallest unit and build your way up. "For components to be reusable and composable, you have to make them as small and as independent as possible." She outlines to pay attention to FUNCTION, or 'type' of component as well. If you have three different components all of the same/similar size whose role is to display text, you need one component, not three.

Split the page design visually into components; structure our folders to follow a consistent pattern; build components starting from the smallest atomic elements to the largest.

"We're not designing pages, we're designing systems of components"

When building in React, start with a mock.
Break the UI into a component hierarchy. *draw boxes around every component an subcomponent*
Build a STATIC VERSION in React
Identify the minimal representation of UI state
Identify WHERE (in what components?) your state should live
Data doesn't flow from the top down, it flows from the bottom up

A callback is a function that is excuted after another function has finished executing. It is a function that is passed as a parameter to another function, and the callback function is run inside of the function it was passed to. A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

Conjunction junctioooooon, Callback function, what's you're functiooooooon?

*First-class functions means, that functions are treated like ANY OTHER VARIABLE*

Let's (not) all get on the class bus! I GUESS it's true that a Class is a kind of function in JavaScript. One big function, that contains other functions, and properties like an object. You can instantiate an object of a class by using the 'new' keyword.

***WOW WOW WOW, I DIDN'T THINK OF IT LIKE THIS: Arrow functions are special: they don’t have their “own” this. If we reference this from such a function, it’s taken from the outer “normal” function.***