---
layout: post
title:      "Rails Portfolio Project"
date:       2020-08-03 02:18:44 +0000
permalink:  rails_portfolio_project
---


The rails project was far more complex than the sinatra one in my opinion. Sure rails has a huge amount of shortcuts but tons more files that are altered than sinatra. So for starters, i coded a good bit of my rails website before i even tested it with rails s and i ended up regretting this due to the fact that i ran into a problem with 'yarn'. Yarn is a dependency file that rails 6+ requires without it being a gem. This caused problems that made me not able to run 'rails s', so i downloaded yarn uninstalled the gem and tried again but still no good. After googling for about an hour or two and trying about 8 different 'fixes', i finally found a fix for yarn and got my rails s working. I felt like it was important to include this in my rails blog because i felt that i learned a good amount of knowledge about troubleshooting compatibility issues or gem problems and finding a fix for them.

The basic files or folders like models, db/migrate, routes and some of the controllers were pretty straight forward. The view files were a bit tedious sometimes because i had to refer to the previous lessons a number of times for methods i didnt remember. I ran into a couple of errors due to some simple mistakes here and there such as accepting a :username value at the login instead of :name (which is what i had it as in my model file). It was omniauth that i just couldnt get down, i tried doing github omniauth, google omniauth, and facebook omniauth but no look on any of them. I tried several ways of doing, watched tutorials, and altered files but still couldnt get it working. I am submitting the project without a working omniauth in hopes that the reviewer of my project gives me some good constructive criticism as to what i was doing wrong and point me in the right direction.
