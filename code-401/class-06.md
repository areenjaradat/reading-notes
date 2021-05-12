# Authentication

1. Explain what a “Singleton” is (in Computer Science terms)

A `singleton` is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.

The singleton pattern is used in programming languages such as Java and .NET to define a global variable. A single object used across systems remains constant and needs to be defined only once rather than many times.

2. Explain how the Singleton pattern can be used with Node modules, specifically with classes

software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. 

3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

```
const express = require('express');
const app = express();

app.use((req, res, next) => {
  console.log(req);
  next();
});

app.get('/', (req, res, next) => {
  res.send('Welcome Home');
});

app.listen(3000);
```

`Router Middleware`are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

`Dynamic Module Loading`is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.

`Singleton Pattern`The singleton pattern is one of the simplest design patterns. Sometimes we need to have only one instance of our class for example a single DB connection shared by multiple objects as creating a separate DB connection for every object may be costly.

`CRUD -> REST Method Matches`REST Method Matches: create --> POST, read --> GET, update --> PUT/PATCH, delete --> DELETE

`Mock Testing`Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.