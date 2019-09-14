---
layout: post
title:      "Cli Data Gem Portfolio Project"
date:       2019-09-14 23:17:59 +0000
permalink:  cli_data_gem_portfolio_project
---


This was my first project that I was assigned in flatiron and it showed me some interesting things about how OOP worked and how to scrape a website. Before i even started my project, i struggled to get the local environment for it to work and had to get some assistance from one of my cohort leads. The problem was that my computer wasn't allowing my terminal to connect properly and after about two or so hours total of messing with the settings, we finally got it to work. The next issue was that despite being properly set up, the terminal would only connect sometimes and the only fix i had at the time was restarting my computer and immediately opening up vscode. I later found out with some testing, that my antivirus was affecting the terminal from connecting, so i gave it access and i was finally ready to start my project.

Making the initial files was easy and i didn't really struggle until i tried scraping my website. The whole process of scraping and nokogiri was still very new to me and after some explaining from a cohort lead, i managed to understand better. I built my scraper and moved on to my file that initialized and stored my objects. Finally, i was on the last part, my cli file, it was pretty simple calling what needed to be called and asking for user input but than i ran into a problem. When i was making my method that allowed a user to either pick another choice, exit the gem, or give an error for an invalid input, i noticed when the user picked yes it was stacking the previous objects with the new ones. For some reason i could not figure out why and than i realized that when i repeated the call method to run the program again, i was not emptying out my previously stored objects. So i made a method in my file where i stored the objects, that cleared the stored data when the user wished to select another option.

After all my errors were fixed i had finally made my first cli program and it was a bit complicated at times, mostly because of the scraping, but it was fun and a great learning experience. I'm really looking forward to learning more about programming and getting closer to getting that amazing programmer job.
