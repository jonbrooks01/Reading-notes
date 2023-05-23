# Class 12 Reading Notes

## Status Codes Based on REST Methods

1)

- 100's = These are information codes, telling the client that the request has been received and they will try to send the requested data
- 200's = These codes mean that the request was accepted, however the information hasn't been sent yet
- 300's = These are redirection codes, saying the information isn't in the current path and they have moved it to a different direction
- 400's = These are Client error codes, stating that the request was invalid i.e wrong URL or the browser timed out
- 500's = These are Server error codes, either the server is busy at the time and cannot reach the information or unreachable behind proxies.

2) The 202 code means that the request accepted but will process the request in the future.

3) The 308 code means that the information isn't where the URL sent the client to and to use a different URL

4) Code 204 would be used to tell the client that the update didn't return the data.

5) Code 410 would be used to tell the client that the information existed in the past but it is gone.

6) Code 403 is the forbidden code, saying the client doesn't have the authorization to access the data.

## Build a REST API with Node.js, Express and MongoDB

1) You need to pull the MongoDB database string out of the server and put it into the env file to make the code more dynamic since the server is going to connect to an outside source instead of local host.

2) Middleware is code that runs when the server gets a request but before it gets past to the routes

3) app.use(express.JSON()) allows the server to accept JSON as the body instead a post element or a get element.

4) /:id acts as a parameter accessing any information that is processed after the '/'

5) PATCH only updates what the user passes through, PUT updates all the parameters.

6) You can include the default object in the schema that will default it to whatever the default information will be

7) The 500 Code means that there is an error on the server and it has nothing to do with the user or client that is using the API

8) Code 201 signifies that the user has created an object vs the 200 code which means that everything is successful.