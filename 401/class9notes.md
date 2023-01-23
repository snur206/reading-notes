# [Class 9 Reading Notes](https://github.com/snur206/reading-notes/blob/main/401/class9notes.md)

This topic matters because it is an introduction to Java HTTP.

## Review: High-level HTTP

This reading is giving us a tutorial on how to request and perform HTTP requests using the HttpUrlConnection class. HttpUrlConnection class let’s us perform basic HTTP requests without using any extra libraries because the classes that are needed is are apart of the package java.net. openConnection() method from the URL class is how you would create the HttpUrlConnection instance. To add parameters to a request you set doOutput property to true, then write a String of the form param1=value¶m2=value to the OutputStream in the HttpUrlConnection instance. setRequestProperty() method is used to add headers to a request

## Java HTTP Request example

Going over the HTTP request cycle with five steps. 

Step 1: Local Processing- Request being made by the browser.

Step 2: Resolve an IP- Client having an IP address.

Step 3: Establish a TCP Connection- Client having TCP Connection.

Step 4: Send an HTTP Request- Client having an IP address and a TCP Connection to send HTTP requests.

Step 5: Tearing Down and Cleaning Up- An HTTP transaction being done.

## Things I want to know more about

HTTP requests in Java compared to JS.
