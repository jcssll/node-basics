# node-basics
basic concepts

The first line uses the require function to load a built-in Node module called http. It puts this lovely module inside of a variable called http. For more about the require function, check out Nodejitsu's docs.

Then we put a server in a variable called app by using http.createServer. This takes a function that listens for requests. We'll get back to this in a minute because they're Super Duper Important. Skip over it for the next two sentences.

The last thing we do is tell the server to listen for requests coming in on port 1337, and then we just log that out. And then we're in business.