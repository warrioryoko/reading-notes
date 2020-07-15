JavaScript Chapter 3

In JavaScript, you declare object literals using curly brace notation {}.

Let fooBieBoo = { someBlah: 'lorax', greenEggs: 'ham' }

What were variables, are now called properties, set using colons. Any functions declared within the curly braces of an object literal, is now called a method and is called/invoked using dot notation.

JavaScript Chapter 5

This chapter was a lot of bloat to expand on methods we had already been using, and are similar in spirit to what we've been using to manipulate the DOM.

The Document Object Model is a model of the contents of a webpage - including whatever JavaScript methods are built-in. This includes the Global, and Window objects. DOMs are laid out into tree data structures, and each element is called a node.

There's a phrase, "DOM Traversal" because you can access nearby nodes in the DOM Tree once you've accessed a node, by referencing the siblings, parents or children.

We're able to access DOM nodes (elements) by more than ID and class. We can grab nodes by class name, tag name, by all common CSS elements, etc.

We can likewise directly manipulate the dom, by accessing and assigning the .nodeValue, creating, appending and deleting elements.