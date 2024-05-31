1 requestHandler: the function reads the request (req) and determine what response (res) to send
2 server: The createServer() method is defined with the request handler because there is only one request handler, the server will allways respond with the same response. in a real world app, you would have multiple requests handlers to handle diff types of requests and diff routes
3 server.listen: The listen() method is invoked with a specified port  after the the call to the listen() method , the server is ready to accept client requests. When run locally, the app will be available on http://localhost:3000.The console.log statement is executed to let the developer know that the server is ready to use


Express.js code 
multiple styles of functions:
callback in server.listen(PORT string, callback _function)
arrow function in requestHandler = (req,res) => {} which has diff scope rules than a regular function

Express.js framework

Route management in Express
http://localhost:3000/products

