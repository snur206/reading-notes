# [Class 8 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class8notes.md)

This topic matters because 

## API Design Best Practices

REST stand for Representational State Transfer.

REST APIs are designed around a resources, which are any kind of object, data, or service that can be accessed by the client.

An identifier of a resource is a URI that uniquely identifies that resource. For example, https://adventure-works.com/orders/1

The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.

The URIs should be based on it's own unique URI.

An example of a good URI would be https://adventure-works.com/orders

To have a ‘chatty’ web API is a bad thing, it happens where web APIs that expose a large number of small resources. The more requests the more loads

The status code does a successful GET request returns HTTP status code 200 (OK)

The status code does an unsuccessful GET request returns 404 (Not Found).

The status code does a successful POST request returns HTTP status code 201 (Created).

The status code does a successful DELETE request returns HTTP status code 204 (No Content).

## Things I want to know more about

Rest APIs and how it would be implemented in the course.
