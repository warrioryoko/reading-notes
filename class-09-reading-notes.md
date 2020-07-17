HTML Chapter 7

Forms are the primary way to allow data collection, if not interaction in general with users within a webpage.

Forms use the the 'form' element, and has an action and method property. Action being where the contents of the form are being sent to, method being the HTTP verb GET or POST.

'Input' elements create different kinds of input form controls, depending on the 'type' property - text, textarea, password, radio, checkbox, date, email, search.

Dropdown menus are created using the 'select' element, and the individual selectable options are created by nested 'option' elements.

The 'label' element has multiple uses, including labeling what form input fields are for. The 'fieldset' element visually groups related inputs or controls together, as well as structurally. The 'legend' element, used immediately after the fieldset element gives a text caption for what the related group of inputs are for.

HTML Chapter 14

If you were so inclined, you could go all /\/\icro$haft Werd CRAZY, and use inherent properties of lists to change the bullet points. 'list-style-type', even 'list-style-image' to place small images/icons for the bullets, with 'list-style-position' to control the level of indentation; 'list-style' is the shorthand that allows you to control all of these with the same property.

Similarly, you can go all /\/\icro$hshaft Excel CRAZY with editing properties of tables in HTML, rather than being a good little coder and using CSS like you should. That is, you can set padding, text-transform, letter-spacing, font-size, borders on the top or bottom, :hover, background-color, alternate shading, decide what to do with 'empty-cells' (show, hide, inherit), determine border-spacing and border-collapse...

...similarly, you can style and align inputs and form controls using innate properties...

...just a bevy of things that honestly, would probably cause me to slap the teeth out of whomever's mouth that used them, instead of placing them into CSS where I'd expect to see them. WHY would you put any of this into your HTML anymore? WHY?

JavaScript Chapter 6

Wow, you KNOW something is BAD NEWS BEARS if THIS book tells you never to use something, like HTML Event Handler Attributes. So, let's not, but say we did. Or maybe never talk about them again, instead.

Gee golly willicker, there's a HUGE list of event listeners that I'm sure I'll look up, rather than memorize. Maybe meimoize.

The event object is a thing, and its shorthand is 'e'. Noted.

You can set event listeners that conditionally do a lot of things by placing them on a parent element, instead of a listener for each individual element that has interactivity. The 'preventDefault()' method is REALLY important if we don't want a webpage or a form to submit and redirect, whenever a 'submit' button and event is fired.

There's all sorts of events that can be fired, the most common being mouse events (click, hover, focus, blur) and form events. There's DOM manipulation events that I'm sure people used to use back in the days of Netscape Navigator. Do we even, today? SHOULD we even?