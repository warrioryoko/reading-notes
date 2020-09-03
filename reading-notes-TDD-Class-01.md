Promises

Makes more sense, actually reading and digesting the MDN a little. Promises are what are RETURNED in the asynchronous promise operation - or a "Promise Object" that is pending, until it actually has the data requested (or failed) and is "resolved".

Destructuring

WITCHCRAFT!!!

I don't like this, and I don't understand what the use cases would be where leaving things this degree of implicit are beneficial or otherwise make your code more readable. I have to play with it and maybe see a few articles with destructuring being used, to convince me most of the possible syntactic uses MDN shows are desirable.

Spread

Yeah, makes sense. I like it.

Rest

Wait, what *$#&

They couldn't provide a definition that wasn't some reduce BS? I don't see exactly why I want to use this, or what it means, or why I should care.

TDD, Where did it all go wrong

Excuse me, while I sniff as often as I say words. I got really bad closer to the end.

Okay, joking aside, this was a PHENOMENAL talk. It's something I'm going to have to come back to. Even while I understand the purpose, gains, and arguments against TDD, it feels like there's some much meaning in what he says that I can't grasp everything from where I am now.

But, absolutely, your tests drive your development. And after you messily implement your code using Red, Green, Refactor into Green - you understand what the problem is and how to solve it... and use the refactoring as your actual "Design" process to think about how you will go about solving the problem.

And you are writing tests for "Requirements", or behaviors... NOT for implementation details. So much good stuff! I listened to this while walking and enjoying the sunshine, it's extremely thought-provoking.

What the heck is the event loop anyway

Well, something that interacts executes things from the top of the call stack, and potentially places asynchronous operations in a queue to be placed back into the call stack later.