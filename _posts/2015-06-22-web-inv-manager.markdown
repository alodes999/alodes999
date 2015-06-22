---
layout: post
title:  "Web Inventory Manager"
date:   2015-06-22 
categories: code
---

This project marks our first foray into linking Ruby and html.  We're using a pretty nifty Ruby gem called Sinatra, which is a nice route handler that directs our page clicks and generates our html from "views" we make.  The extra nifty part is that our views are written as .erb files, or embedded Ruby files.  It's like html, but we can put Ruby code into those html documents.  For my project, as a specific use case, it helps being able to use that Ruby to bring in extra user ease when making changes to already stored values; for example, in my Change Ship page, the ability to use Ruby lets me bring in dynamic values that the user can change.  That means I grab what ship they want to change, and I send back the ship's row from the database as pre-filled values that they can then change how they want.  Without the Ruby, it would be pretty hard, at least from what we know so far, to bring in those default values that are tied to the ship we want to modify.

So far, after some initial hesitation and frustration on what to start on, I think this has been a pretty easy to do project.  It did help we did this on our command line, and hammered out that functionality there.  The port over to the website has been quite easy, as it was just a simple "get this to work the same as your command line", and since it's on a webpage, a lot of the "go back" functionality is handled with a simple "Go home" link.

This isn't ported to an actual website yet, but Sinatra does let you run it on a web browser as localhost.  Here's a link to the repository that holds this project, in case you'd like to take a peek at the code or what have you:

<a href="https://github.com/alodes999/6-19-web-sqlproject">github.com/alodes999/6-19-web-sqlproject</a>


We're still working on refining the pages and adding new functionality, but for a start, I think it's a pretty solid foundation for what we'll be adding in the future.  Sometime this week we'll be working on a new project, so that's going to be exciting.  We do have to go over CSS and other stuff first, so we'll have some more building on what we have learned.