# Generate Prime Numbers

## Objective
To understand how to use web workers.

## Notes
**Workers** enable you to run some tasks in a separate thread of execution.

<br>

*"if multiple threads can have access to the same shared data, it's possible for them to change it independently and unexpectedly (with respect to each other). This can cause bugs that are hard to find."*

<br>

**"To avoid these problems on the web, your main code and your worker code never get direct access to each other's variables, and can only truly "share" data in very specific cases.**

- Workers and the main code run in completely separate worlds, and only interact by sending each other messages. 

- In particular, this means that workers can't access the DOM (the window, document, page elements, and so on)."

<br>

-MDN Web Docs / Introducing Workers : https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Introducing_workers
