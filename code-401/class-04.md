# Data Modeling

* Name 3 advantages to Test Driven Development

1. Writing the tests first requires you to really consider what do you want from the code.
2. You receive fast feedback.
3. TDD creates a detailed specification.
4. TDD reduces time spent on rework.

* In what case would you need to use beforeEach() or afterEach() in a test suite?
If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.

* What is one downside of Test Driven Development

It seems slower at the beginning: If you start TDD, you will get the feeling that you need a longer duration of time for easy implementations. You need to think about the interfaces, write the test code, and run the tests before you can finally start writing the code.

* What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

```
 Classes can’t be called without new, but functions intended as constructors can

 Classes can extend more types than constructors can (like functions and arrays)

 Classes prototypes are their parents (they inherit static properties); writers of constructor functions usually don’t bother with this

 Non-classes can’t extend classes (because they can’t call the parent constructor)
```

* Why REST?

```
REST is Easy to Understand and Implement
REST is meant to work over HTTP. Therefore it makes use of HTTP verbs that most of us know, such as GET, POST, and PUT.
the clear separation of client and server code makes it easy for different teams to work on different parts (front end or back end) of applications.
```

`Functional programming` is a programming paradigm, meaning that it is a way of thinking about software construction based on some fundamental

`Object-oriented programming (OOP)` is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.

`Classes` are a template for creating objects. They encapsulate data with code to work on that data. 

The `super` keyword is used to access and call functions on an object's parent.

`this` keyword refers to the object it belongs to

`TDD`: is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. This is opposed to software being developed first and test cases created later.

`Jest` is a delightful JavaScript Testing Framework with a focus on simplicity.

`Continuous integration (CI)` is the practice of automating the integration of code changes from multiple contributors into a single software project.

`REST` (Representational state transfer) style used to create web app by using HTTP requests

`Data modeling` (data modelling) is the process of creating a data model for the data to be stored in a database.
