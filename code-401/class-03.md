# Class 03 Reading Notes

## Review: ES6 Classes

1) Classes are a template for creating objects.

2) Classes have the same declaration as temporal dead zone restrictions like 'const' or 'let'. They cannot be hoisted.

3) You can think of a constructor as a blueprint for the object, its like a recipe that tells the computer how to create a certain object. The 'this' refers to the properties and methods inside the object, using 'this' allows you to access the properties within that object.

## Using Express Routing

1) Routing refers to how an applications endpoints respond to a clients request.

2) Route method refers to the CRUD methods allowing the user to retrieve something or update something based on the request. A route path is a combination with a request method, they define the endpoints at which requests can be made.

3) you can add the next route to bypass the remaining route callbacks. This way there are preconditions invoked on the path and the control of the route is passed to the subsequent route.

## Express Routing

1) Express Router is a mini express application there aren't any views or settings but we are able to use the .use,.get,.param and route with the express.router

2) You can create an instance of express router by declaring it to a variable and using that variable in subsequent code.

3) route middleware is used to ensure the user is authenticate, logging any data for analytics or anything else the developer will need to do before the information is sent to the user.

## Reflection

1) I would like to understand how to effectively use SQL in code and how to apply it properly.
