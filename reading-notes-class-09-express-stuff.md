Supertest

Another testing module? So, it looks like we can write a test slightly easier, by using 'expect', in the same form as our express app calls. The examples show that we can chain some things that might be convenient, such as info on responses.

Is there something it does for us, that Jest doesn't do? Weren't we able to otherwise do this using Jest, or some reason why Supertest is better?

"...Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle..."

Okay, question answered.

"...body-parser
This is used to parse the body of requests which have payloads attached to them..."

So, you're saying, that we could just use something like this instead of having to write our own parsing for the response? -__________-

Express seems to be nothing, if not middleware that allows us to chain together a bunch of middleware conveniently on top of Node.

I will say, as I read this, I found myself feeling it easier to read official documentation. Seems a lot less exotic and painful now.

