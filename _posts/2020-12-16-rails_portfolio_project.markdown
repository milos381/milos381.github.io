---
layout: post
title:      "Rails Portfolio Project"
date:       2020-12-17 02:50:28 +0000
permalink:  rails_portfolio_project
---


What can I say, I am (hopefully) done with Rails project, too.

My StoreApp consists of four models: Model (of the phone), Phone (phone make), User and Purchase.

Phone and User are connected trough has_many through relationship, and Phone and Model are connected through has many/belongs to, relationship.

The creation of the phone and all the models are trough the Phone controller. Even thou we exercised creation of artists through songs, we never did it the other way around in the labs, so figuring out the way how to do it and showing the results (iteration inside of iteration) was maybe a logical step, but it took me a day to get there.

Dealing with has many through relationsip was relatively easy, considering we had so many labs that focused on that exact issue. The big help for me was relalizing that hidden_field is the one that is carrying the necessary info without showing it to the user, thus allowing us to acomplish the goal of (in my app) purchasing the phone.

Since every user has to have some money to buy a phone (sorry, we can't give it for "free" like att), I had a problem to figure out how to add money to users logged in trough omniauth, but then I realized by simply adding it trough a line `u.money = 1000` in the sessions controller it made it possible.

I made sure all the requirements are fulfilled, from nested routes, to validations. Was it easy? No,  it was not, but this project help me get a deeper understanding of CRUD in Ruby on Rails, since it took me a lot of searching, googling and asking questions.
