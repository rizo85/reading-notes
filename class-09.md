# Error handling and debugging

[Back to Home](https://rizo85.github.io/reading-notes/)

### JS

##### Errors in JS

Errors are what cause the JS to stop and give us a message. This is important ti thry and catch or handle so that if some of our code breaks we can still execute other functionalities instead of a full on stop on our applications.

#### The most important summary of error handling is:

- The try statement lets you test a block of code for errors.

- The catch statement lets you handle the error.

- The throw statement lets you create custom errors.

- The finally statement lets you execute code, after try and catch, regardless of the result.

We can wrap risky code in a try catch and *sometimes* finally statement, understanding how each one operates will make or break our code.

Some errors we can handle, but some errors are impossible to, and it seems that the best way to solve them is to make sure we follow proper naming convention, type of our variables, and track back where our references are pointing to when things are amiss.

![Events]( https://javascript.info/article/try-catch/try-catch-flow.svg)


[Back to Home](https://rizo85.github.io/reading-notes/)
