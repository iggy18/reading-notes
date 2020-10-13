## explaining REST to my brother
 
- roy fielding helped write the first web servers.
- http tells the brows what protocall to use. 
- REST provides a definition of a resource.
- urls tell the browser that there is a concept somwhere and the browser can go get a representation of that concept.
- we are trying to get computers to be able to talk to ALL other computers at the same time.
- when a computer doesn't have something it will use a redirect to a computer that does.
- when you go to a web page, the browser does an HTTP GET on the URL you type in and back comes a web page
- If one system needs to add something to another system, it would use an HTTP POST.
- If a system wants to replace something in another system, it uses an HTTP PUT, or, to do a partial update, it'll use PATCH.

## super agent 
- SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!
- A request can be initiated by invoking the appropriate method on the request object, then calling `.then()` or `.end()` to send the request.
Old-style callbacks are also supported, but not recommended. Instead of `.then()` you can call `.end():`
- When given the .retry() method, SuperAgent will automatically retry requests, if they fail in a way that is transient or could be due to a flaky Internet connection.