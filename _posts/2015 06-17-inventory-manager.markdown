---
layout: post
title:  "Inventory Manager Project"
date:   2015-06-17  
categories: code
---

# Inventory Manager Project

This past weekend we were tasked with coming up with a Inventory Manager database program.  There were quite a bit of requirements and details about how we were to go about it, certain naming conventions we were to use, and a general format for it all.  I will say getting the SQL to work wasn't all that difficult.  We didn't do too deep of a dive into the various commands we could use, staying with the general CRUD uses for SQL (SQLite in our case.)

My take on the project went with my previous experience with an online game, EVE Online.  I used ships as my "items" table, ship _types as my "Categories" table, and ship _locations as my "Locations" table.  I made a short video detailing the final command line product, as well as going over my ShipName class.  I only did one class, since the rest were pretty similar to that, and I didn't want to bloat the video explaining basically the same methods over and over!  So the video: 

<iframe width="420" height="315" src="https://www.youtube.com/embed/odsRiOyaIkI" frameborder="0" allowfullscreen></iframe>

We've spent yesterday and today refactoring our code for ORM purposes, basically dealing with Objects, and leave the hashes we get from SQL as something only Ruby has to deal with, and not our users.  That presented some challenges, as going back through code is a "fun" task, but doing it over and over again is the best way to practice what we'll need later on, so it's "fun" with a solid purpose

In the end it's been a pretty good project, and I really felt like it was something I could pretty decently feel my way through.  I think my biggest obstacle right now is myself, trying to convince myself that I can do this while getting that nagging "This is WAYYYYYY over you" static in the back of my head.  Getting through each project is just another way to show myself "Yes I can, hater be damned!"

Coming up, HTML and CSS.  More language goodness! (Yes, I'm excited, and still slightly overwhelmed.  It's kind of a constant feeling the past few weeks!)