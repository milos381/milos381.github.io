---
layout: post
title:      "Javascript with Rails api project"
date:       2021-01-21 01:29:11 +0000
permalink:  javascript_with_rails_api_project
---


Step four out of five. Personaly for me, one of the hardest ones so far.

I had many problems when I started working on this project. The first one was to choose the project I want to work on. 

First thing that came to my mind was to make an instagram clone project. I made a schema, but I decided that with the knowledge I have, I want to make something that doesn't exist, so I made "Neighborhood app".

I imagine a Neighborhood app to be an event-posting app, that will be used between the neighbors that are living in the same neighborhood. 

A Saturday brunch, an unknown person walking by himself at 3am or maybe a stranded car, neighbors will now have a platform to exchange messages. 

The app has three different fetch requests. The first one is to load all of the existing events, second one to delete an existing event and a third to post a new event.

As for the backend, it consists of three models and controllers (Family, Event and Report), where we are using Event json in order to create,delete and load our json objects.

When we are creating a new event, in the same "create" method we are creating a report (headline and content of an event) and a family who is posting that event.

There was a more simple solution, to just exclude events and use family and reports, but I've realized with my last project that I want to come back one day and add more options and expand functionality of my projects, once my knowledge increases. 

As for the looks of my app, it is very minimalistic - nice fonts, simple layout and good functionality.
