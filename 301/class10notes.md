# [Class 10 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class10notes.md)

This topic matters because the topic is diving into javascript errors and call stack

## Understanding the JavaScript Call Stack

A call is used to manage function invocation. Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

One is the amount of times 'calls' can happen at once.

LIFO means Last In, First Out.

An example of a call stack and function needed to be invoked to generate a call stack:

``
function firstFunction(){
  console.log("Hello from firstFunction");
}
function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
``

A stack overflow is caused when a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages

A reference error is you try to use a variable that is not yet declared you get this type os errors.

A syntax error is when you have something that cannot be parsed in terms of syntax.

A range error is when you try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.









#### Things I want to know more about

A
