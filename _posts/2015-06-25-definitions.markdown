---
layout: post
title:  "Definitions"
date:   2015-06-25
categories: code
---

Sumeet's next assignment portion is some defining of concepts.  He gave us a list of terms, and has asked us to define them to the best of our ability!  So, here we go!

- What is a class?
<p>A class is a collection of methods that make up the behavior of the Objects that class can create.  We can define our own, often having to, because the core Ruby Object can't define everything ever, however awesome that would be.  Being able to define the behaviors and attributes that would make up a Class is one of the biggest portions of learning Ruby, in my opinion, because we need the Objects we create using the Class methods and attributes to interact with.</p>

- What is a model?
<p>A model is a class that interacts with a Database table.  The models' attributes match the tables' column names, and the methods for the model are used to interact with the Database in various ways.  it's helpful to use the model for interacting with Ruby because pushing the Database records into Ruby Objects allow us to interact with and manipulate that data in much easier and more numerous ways than we could with just the raw Database data.</p>

- What is a method?
<p>A method is a behavior of a class, or model.  It's what we can call to make the Object (for instance methods) or the Class (for class methods) do something in relation to the data in the class/model.</p>

- What is a variable?
<p>A variable is something we define to store some piece of data to manipulate or interact with.  Variables can hold anything, strings, integers, boolean values, arrays, hashes, objects, even 'nil'. They are something we work with on a constant basis.</p>

- What is a request?
<p>A request is something a web application uses as a user input.  The user does something, and that something sends a request to our program on the server.</p>

- What is a route?
<p>A route is something we define that handles the requests our web applications receive.  It takes the "message" and directs it to where it needs to go for the program to process what it needs to.</p>

- In the context of a web application, what is a "response"?
<p>A response is the view(the webpage) that our web application sends back to the user so they may proceed, either with the page, or with the information they've requested.  The basic model for the last 3 questions is something like this:

User sends a request (Clicking a link) ->  Our program has a route defined that grabs the request and processes it ->  Our program sends back a response (New page loading up) to the user, so they can continue their trip.</p>

