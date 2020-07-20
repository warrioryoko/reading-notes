JavaScript Chapter 10

I don't have a good way to clearly describe the order of execution of JavaScript, and the stack. There IS a stack, where JS gathers information from other blocks in increasingly higher levels up to the global object, which makes what it is executing meander around.

Come to think of it, execution context is another really awkward idea to clearly describe in words. I'm not going to do it, I wouldn't do better than the book at this time, or otherwise just end up repeating what it says verbatim.

Actually, everything with Scope, Hoisting and execution context is REALLY not explained well. In the text, there's nothing relating it to anything else or any metaphors, just a dry explanation 'this is what it does'. I read it carefully, and I'm walking away without being able to articulate "what" it is I read exactly.

When JS encounters a problem with the script that it cannot resolve, it generates an error object. We generally want to avoid this, because this is a result that causes the program/script to stop running entirely.

So, using Try/Catch and possibly Finally is a better way of handling data and operations that we anticipate could cause issues rather than allowing the program to explode.

There's a few interesting console methods I can try out, such as grouping. Breakpoints and stepping through code using the breakpoints are a debugging technique I should start using more - too bad that they don't seem to be something you should or can use before you run into an actual problem.

HTML Chapter 15

Reading this again, having more time forced to play around with CSS, I realize a few things deeper.

Fixed sizes are absolutely the devil (unless they are minimums, maybe) and should be avoided like a wet puddle of cat vomit.

I don't know why I didn't really notice the 960.gs layout before, and I don't understand how they got the output to look so clean. I'm going to ask about it in class.

It seens there is an art to using floats correctly, and they go to great pains to describe multi-column floats and common issues with floats. I guess this is an area of plain CSS that I should really look into and play with more.