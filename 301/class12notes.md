# [Class 12 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class12notes.md)

This topic matters because this topic is discussing errors and MongoDB.

## Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:

- 100’s = That it will be working on resolving the error/comply with the clients demand.

- 200’s = Code is successful and the request is accepted

- 300’s = The resource the client is requesting is not available at that location

- 400’s = Client error issues where the clients request is invalid like a wrong URL.

- 500’s = Unreachable server request. Server error code.

A status code 202 tells the client that the request was valid, but its processing will finish sometime in the future.

A status code 308 tells the client to use another URL to access the resource and not use the current URL anymore. 

The code would you use if an update didn’t return data to a client would be 204 No Content status code.

The code would you use if a resource used to exist but no longer does would be 404 Not Found status code.

 The ‘Forbidden’ status code is the status code 403 Forbidden, where the client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## Build A REST API With Node.js, Express, & MongoDB - Quick

We need to pull our MongoDB database string out of our server and put it into our .env to make sure nobody is able to see where the server is located.

Middleware is code that runs when the server gets a request but before it gets passed to our routes.

app.use(express.json()) lets the server accept JSON as a body instead of a post element.

/:id means in a route that it is a parameter that we can access by typing in a request. 

The difference between PUT and PATCH is that using PATCH to only update based on what the user passes us and using PUT, you are pushing all the information all at once instead.

To make a default value in a schema by passing Date.now.

A 500 error status code means a server error code where it has nothing to do with the user/client using the API.

The difference between a status 200 and a status 201 is that 200 means that everything was successful and that 201 is more a more specific way to say that you have created something so when you're using a POST route, make sure to send 201 when you're successful instead of 200.

## Things I want to know more about

More of an understanding of MongoDb.
