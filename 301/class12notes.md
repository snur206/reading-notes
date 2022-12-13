# [Class 12 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class12notes.md)

This topic matters because this topic is dicussing errors and MongoDB.

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

We need to pull our MongoDB database string out of our server and put it into our .env 
















## Things I want to know more about

