Node.js programs are NOT executed in a browser!!!

Yes, NVM is the way. Removing, or installing other concurrent Node versions because a project requires an older (or newer!) version can cost a LOT of time, to get working right.

Modern frameworks and libraries, including react, depend on running Node inthe background for the build process and test environment.

Node lets us run JavaScript on/as a server. It is non-blocking, a Node process is SINGLE-THREADED, but uses the event loop. As many processes are Asynchronous, it places tasks in a queue to devote processing time to without refusing additional requests while it is waiting to hear back from other tasks.

Calls that are naturally i/o blocking should be avoided entirely; CPU-intensive operations (calculations, for example) should be handled to a service worker; and we MUST properly handle exception and error handling, because not doing so will crash the server just the same as it ends execution of JavaScript in the browser.

You'll never want to write native Node.js code that deals purely in requests, responses, callbacks - even modern EcmaScript. Node chains multiple callbacks and processes data in VERY discrete steps. It's a nightmare writing, and reading native Node code. Having done that a little, it makes you appreciate that Express.js does that under the hood, so that you don't have to.

Node natively uses JSON - which should make sense, since it's JavaScript. It's used for anything that requires handling of http request/response cycles, including establishing connections with clients on the the web/through web pages, database operations, etc.