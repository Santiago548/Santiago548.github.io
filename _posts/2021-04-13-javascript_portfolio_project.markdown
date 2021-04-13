---
layout: post
title:      "Javascript Portfolio Project"
date:       2021-04-13 15:47:09 +0000
permalink:  javascript_portfolio_project
---


I created this project to help myself and anyone else running a 5E campaign in Dungeons and Dragons to quickly create NPCs.

Utilizing a Rails API for my backend. I created two models, one an NPCs model to help house all the information on created NPCs and an Encounters model to house my encounters id. I created relationships between NPCs and Encounters. The Encounters have many NPCs and NPCs belong to Encounters. I used seed data to create only three encounters so that my users can filter out their NPCs by encounter id and to only allow for three encounters now.

I kept my controllers very dry and encapsulated all my models, serializers so that anyone making changes or improvements can easily read through my code.

for the front end as part of this project requirements, I focused on javascript utilizing CSS to help style my application. this was the most difficult part as I'm not completely familiar with CSS. luckily lots of googling and help from the cohort allowed me to utilize grid functionality to get my page looking exactly how I liked.

future iterations of this application. I will add advanced methods to allow for creating random story hooks. and to add the full encyclopedia of races, spells, weapons, and the like from the full compendium of D&D books.

There is just so much information currently to do that to get to this application at the MVP I opted to keep the information minimal.

The user can use the NPC form to create an NPC fully picking out every stat and ability. However, to make a true Generator I worked to make a Random functionality to allow a user to create a full NPC with just a Name and an encounter. This was a tricky endeavor as in Javascript there are many ways to do one thing and took me some time to find the right one to get it exactly how I needed it. Again, lots of googling and cohort help to fully understand how to use Math and the arrays of the needed information to make it truly random.

lots of work, long days, and stress went into making this. But like everything I've done so far all of it has been worth it to see what's in my head work on the screen

