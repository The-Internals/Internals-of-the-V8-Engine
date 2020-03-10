#  Internals of V8 Engine

## Discussion recoring 

https://youtu.be/4lYDlrjUx48

## Agenda

What is a JavaScript engine?

What happens when a browser comes across a script tag? - The journey of a JavaScript file from downloading to execution.

Different attributes that you can use with scripts - async/defer why you should use them?

Components of V8 - Parser, Interpreter, Compiler

How V8 parses a javascript file
- What is an AST and how a javascript code is converted into an AST
- Lazy and eager parsing
- Heuristics employed by V8 for parsing
- What are scopes and how are they generated by the parser?
- What is Just in time compilation and how V8 uses that?

What is a bytecode?

How V8 compiles and interpretes the bytecode?

Optimizations done by V8

Understanding Object Model - How V8 makes some optimizations based on the shapes of the objects

Understanding Arrays
- Why you shouldn't have holes in your arrays
- Optimizations done by V8 based on the type of elements stored in arrays

What is hot code and how V8 decides that a particular snippet of code is hot?

What are inline caches?


## Resources:
- JS Engine Fundamental
https://youtu.be/0I0d8LkDqyc

- The Journey of JavaScript: from Downloading Scripts to Execution - Part I
https://www.telerik.com/blogs/journey-of-javascript-downloading-scripts-to-execution-part-i

- The Journey of JavaScript: from Downloading Scripts to Execution - Part 2
https://www.telerik.com/blogs/journey-of-javascript-downloading-scripts-to-execution-part-ii

- The Journey of JavaScript: from Downloading Scripts to Execution - Part 3
https://www.telerik.com/blogs/journey-of-javascript-downloading-scripts-to-execution-part-iii

- Parsing JavaScript - better lazy than eager?
https://www.youtube.com/watch?v=Fg7niTmNNLg

- JavaScript engines - how do they even work?
https://www.youtube.com/watch?v=p-iiEDtpy6I

Intro on how JS engine creates and maintains environment record and life-cycle of a variable depends on it
(Understanding environment record and variable life-cycle involves reading from multiple sources, as there is not a single page that describes all of it together)

- Variable Life-Cycle
https://dmitripavlutin.com/variables-lifecycle-and-why-let-is-not-hoisted/

- Execution Context, Stack and Records
https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/
http://davidshariff.com/blog/what-is-the-execution-context-in-javascript/
https://levelup.gitconnected.com/learn-javascript-fundamentals-scope-context-execution-context-9fe8673b3164
https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0
