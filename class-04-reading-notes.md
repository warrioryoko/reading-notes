HTML Chapter 4

Links use the anchor tag, <a> and requires an href attribute with a relative
or absolute URL to tell the browser where to navigate to.

Absolute links include a domain name, relative links are links relative to the location of the html file in its root directory.

The book spends ~4 pages exhaustively going through the idea of family tree terminology that I found entirely overcomplicated and unnecessary.

You can start a user's default email program using an anchor tag by prefacing the href with mailto:

You can also force the web browser to open links in a new window by using the target attribute with a value of _blank.

Finally, you can link to specific parts of a relative or absolute URL in the value of the href attribute of an anchor tag, by referencing the CSS id attribute of the location you want the browser window to focus on. By referencing something like <a href"#this-cool-story"> you're able to move the browser to the beginning of that named element.

HTML Chapter 15

Block-level elements begin on a new line and do not normally "wrap" or flow alongside other elements.

Inline elements flow in between surrounding elements. Elements can contain other elements.

There are four main positioning schemes that break from normal flow, AND THEY ARE ALL TERRIBLE IDEAS, EACH AND EVERY ONE OF THEM. USE FLEXBOX AND GRID INSTEAD OF USING ANY OF THESE EVER, THEY NEVER DO WHAT YOU WANT THEM TO DO.

Relative positioning - moving an element a number of units relative to where it would otherwise have been; absolute positioning which puts it in a fixed position like nailing it to the wall, and it will never move; fixed positioning which is one of the most obnoxious ideas ever, which absolutely places the element in an absolute position relative to the view window much like holding a piece of paper in front of your face regardless of whether you turn your head; and floating eements - the secrets of which NOBODY has successfully discovered. Not even Gandalf the Grey Wizard understands how float actually works, or can predict how it will turn out.

JS Chapter 3

So there are these things called functions that we've already been using for at least 3 weeks, if you dont count pre-work done before prep week.

They sometimes take arguments, sometimes they don't. They can be writen as a declaration - function fooBar(some, stuff) { return goesHere };

They can be written as an expression, where they are assigned to a value - const mcPeePeePants = function changeDiaper(more, stuff) { return cleanPants };

They can also be written as and IIFE, when you want the anonymous, disposable size - let forTheShorties = (function() { let iLikeCandyBubblegumAndTaffy = 'gettothesweetshop'; }());

This executes the function immediately, and assigns its execution VALUE to the variable forTheShorties rather than store the function itself to the variable.

Variables have different scopes depending on where they're declared. Variables declared within functions are only accessible within the function (allegedly); variables declared globally are availabe to everything in the file.

Pair Programming

Pairing takes slightly more time, but usually produces code that requires less refactoring, ultimately saving exponentially more time than it took to produce. Two heads are usually better than one, and working together to produce code can make each person think much more carefully about what they're doing than if they were working alone. 