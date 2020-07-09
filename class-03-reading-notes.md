HTML Chapter 3

Three kinds of lists

Ordered Lists <ol></ol> - These have numbers
Unordered Lists <ul></ul> - These have bullets
Definition Lists <df></df> and <dd></dd> - These have neither, but keep indentation of list items

You can nest lists, which changes the bullet styling of each level of nesting

HTML/CSS Chapter 13

CSS works off of a box model - everything is an imaginary box. As such, all
HTML elements have properties which can be manipulated as if they are a box container.

width and height: Like you'd expect

min-width and min-height: smallest size a box can be displayed. But what happens when the viewing window is smaller than this? What happens?

max-width and max-height: the box container will be no bigger than this

overflow is a property with a value of hidden, or scroll. This says what happens if the box *content* of the container is larger than the box. I've never seen this, and I wonder if it's within best practices to use it?

Margin: Social distancing, or distance between balloons (HTML element containers)

Padding: Thickness of the walls of the balloon, or how much space there is between the edges of the ballon(box) and its contents (the air inside of it)

Border: Visible force field of the ballon - like the color of a balloon, if the color could also have a thickness?

Borders have width, and the top, right, bottom and left sides of the box container can have different properties. So, width shorthand for borders IN
THAT CLOCKWISE ORDER is border: 10px(top), 10px(right), 10px(bottom), 10px(left), or border: 10px(top and bottom), 10px(left and right)

You can use the border-width property for this, but why would you want to?
There is also border-style and border-color, which give the border a style
(dashed lines, grooves, ridges, insets) and a color respectively.

To center an element, give it width, and set the left and right margins to auto. Or maybe set the margins to auto in general.

The book doesn't make sense of the text-align property, so I'm not going to use it unless I see it in out in the wild.

You can change the display properties from inline to block, or vice-versa by explicitly defining them using those as display attribute properties. Display 'none' will remove the element entirely, as if it wasn't there.

Visibility 'hidden' makes an element invisible, but the space around it remains.

border-image, box-shadow, and border-radius let you do fancy things with the border or space around the border.

JS Chapter 4

Switch statements are bloated and you probably shouldn't use them unless you've actually got a ton, or unknown number of conditions to test. They require a break statement, and are allegedly more efficient at runtime than if/else. I don't know that this really makes a difference, as we are using a language that has an interpreted runtime component to it, and we're not in the C++ days of memory and processing optimization where we had very limited system resources.

Type coercion is interesting, and makes me appreciate why developers who like strong typing absolutely hate JavaScript. There's truthy and falsy values, and I don't think you should try to be clever and use these, or ever do anything other than be extremely explicit.

You can use the fact that conditions have a short-circuit value to do assignment statements, and I think that's a really dumb idea, too.

For loops do a thing a specified amount of times, while loops do a thing while a condition remains true, and do-while loops are things that C++ programmers use and everyone else probably doesn't have a use for.