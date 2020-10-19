Webpack seems to be doing the same thing as create react app was doing for us... except we now have to explicitly specify everything it's doing, now.

That is, our dependencies have to be spelled out in a script, our entry points and output, our bundling process, and application of babel transpiling. All of these things were done for us by using create react app, and we now have to write a dozen or so lines of configuration code ourselves, using webpack.

Webpack has Loaders, which are instructions on what to do with files other than .js and .json files, and what tool to use to process them. It also has Plugins... which I guess, are imported internal utilities.

There was some remedial reading on basic React. Apparently elements are what make up components; elements just being a presentation element or "what you see". We've been using "App" as our element we pass to reactDOM.render, which contains the whole freaking component/file tree.

Hopefully, we never have to manually use react to create elements.
