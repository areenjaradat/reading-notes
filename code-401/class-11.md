# Event Driven Applications

## Why is access control important?

Access control is important because it is a valuable security technique that can be used to regulate who or what can view or use any given resource.

## Describe an application that would need access control

Account management(username & password)

## What is a role used for?

give the user access to some information and make some edition

## Why is role based access control more scalable than discretionary or mandatory access control?

Role Based Access Control (RBAC), also known as Non discretionary Access Control, takes more of a real world approach to structuring access control. Access under RBAC is based on a user's job function within the organization to which the computer system belongs.

`Authorization` is the function of specifying access rights/privileges to resources, which is related to general information security and computer security, and to access control in particular.

`Role Based Access Control` is an approach to restricting system access to authorized users.

`Capabilities`What can authorized user after login

## Event Driven Programming

Event : is basically a signal that indicates that something has happened in our application , for example in node we have a class called HTTP that we can use to build a web server so we listen on given port and every time we receive a request on that port that http class raises an event, now our job is to respond to that event which basically involve reading that request and returning the right response . several classes in node raises different kinds of events . in event module we have class that is called event emitter it is one of the core building blocks of node and a lot of classes are based on this event emitter .

const EventEmitter = require('events');

EventEmitter is class container for properties and functions which we call methods , to use this method create instance of this class

const emitter = new EventEmitter();

emitter.emit() to raise an event .

listener is a function that will be called when that event
is raised .

emitter.on == emitter.addListener (the same)

Event Driven Architecture (HTTP module , Fs module , url module )

event Emitter -> Event Listener -> callback function
