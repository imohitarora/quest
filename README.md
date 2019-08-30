# quest
questions


1. What is the difference between setTimeout and setImmediate?
      setTimeout(fn, delay) calls the given callback fn after the given delay has ellapsed (in milliseconds).
      However, the callback is not executed immediately at this time, but added to the function queue so that it is executed as soon as
      possible. setImmediate(fn) achieves the same effect, except that it doesn’t use the queue of functions. Instead, it checks the queue
      of I/O event handlers.

2. What is an error-first callback and why we use it?
      First argument is always error.
3. What is callback hell and how to avoid it?
      Executing code in response block only makes code dirty messy and make call back hell.
      a. modularization
      b. use of promise
      c. use yield
4. What is event loop?
      Node.js runs using a single thread, at least from a Node.js developer's point of view. Under the hood Node.js uses many threads
      through libuv.
      Every I/O requires a callback - once they are done they are pushed onto the event loop for execution. 
      
5. What is operational error?
      An issue with system. /timeout/hardware failure
      
6. Can you access DOM in node?
      Nope

7. What is two way binding in Angular?
       two-way data binding really just boils down to event binding and property binding.
