---
layout: post
title:      "Javascript-Rails-Project"
date:       2021-02-02 17:38:18 +0000
permalink:  javascript-rails-project
---


My second time trying to do this project and i can say i have learned different ways of doing things. Firstly i used scaffolding to make the rails api again like last time but this time i used to devise to handle the user signup and authentication. The scaffolding made the the models, controllers, routes, and migations with configurations of my own here and there to make the front end work properly when retrieving data.  I than configured the development files to work with devise properly and configured cors to allows authorization headers and all origins.

For the front end i ran into some trouble at first displaying the selected recipe because it wasnt marking the recipe as 'active'. I had to add a "active"  attribute to the recipes migration in order for it work properly and highlight the recipe. I also ran into an issue with the users not displaying all of the recipes and ingredients on the screen. After a long search i realized that i had made some typos and mispelled some of the methods that were being called on when rendering the recipes. I learned that a simple mistake such as a typo can make you think its something more complex than it really is. My final problem was the deletion button and the edit buttons not working either. This turned out to be similar issue of mispelling method names and putting a wrong } or . in the wrong places. 

The main thing i am finally happy about is that i was able to do a has many relationship this time compared to my last attempt of the first project where i couldnt accomplish that. I believe that going over the material again and watching various videos from both the instructors and on youtube helped me find the mistakes i was making on the project. The project definately took me way longer than it shouldve but i managed to learn from my first mistakes even if it took me a while. I feel like this project in particular has taught me more about being very careful with syntax and that i still need to improve on speed when programming.
