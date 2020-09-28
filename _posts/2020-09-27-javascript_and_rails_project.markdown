---
layout: post
title:      "JavaScript and Rails Project"
date:       2020-09-28 02:40:23 +0000
permalink:  javascript_and_rails_project
---


This project was pretty straightforward except one thing i couldn't get down for some reason. First off making the rails api was pretty easy, i used scaffolding to make the models, controllers, routes, and migrations. The way scaffolding makes these things allows me to not have to setup serializers because the data im using or imputing is not too complex, scaffolding has it set up to where it does that work for me. I than setup my cors.rb files in my config>initializers folder to allow it to communicate with my frontend. With that my rails api was done and i moved onto my front-end.

I set up the index.html file and added the source for my js files, aswell as 2 divs with id's that i can use to get the id for my functions. I made a review.js file that has a constructor that sets up all the data that comes with the review model and a method that puts html into my "reviews_holder" div on my html file. The index.js file has an eventlistener that loads the section to allow a person to input a title and review for submission. The eventlistener also loads all reviews that the database has and automatically reloads the page when a new review is made. I have a fetch request that takes all reviews and renders it to my review.js file that than displays it on the page. I also have a fetch request that renders a new review when a person pressed the submit button for a new review. Finally, there is a third fetch request that occurs when a user deletes a review and reviews the page afterwards.

The project was simple but the one thing i was not able to accomplish was a has many relationship, i'm not sure why i couldn't get it to work but in the end i didn't implement it so that i could have a functioning website. I look forward to my review to see what i did wrong and how i can accomplish that properly. Overall, this project was a good experience to better understand my strengths and weaknesses when it comes to programming.
