DNS

Wow, I wish there were more comics like this - or I knew of more like it!

Resolvers, Root servers, Top Level Domain servers, name servers, oh my!

Nice overview, and I'm glad I read it; how specifically are we supposed to use this knowledge of DNS server hierarchies?

HTTP

Our stateless protocol friend; whereas React.js is our stateful friend?

Things are communicated in request/response pairs. This is what the request/response cycle and arguments we see in Node and Express are modeled after. Client makes a request, server gives a response - including if the request was in a bad format, or failed. We have HTTP VERBS that represent a certain operation be performed, and status codes that indicate what happened as a result in the response from the server.

There's headers that contain information about the client, destination and so on as well as the body that contains the actual payload of the message.

REST

Yeah, the restaurant waiter analogy. APIs are a contract on the form of communication between applications. Make a request in a specific format, get a response in a specific format.

It treats servers as resources that can have their specific ENDPOINTS manipulated using HTTP verbs, with each piece of information or DOCUMENT being an individual URL ENDPOINT.

*Emphasis added