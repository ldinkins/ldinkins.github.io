---
layout: post
title:  "Assignment Five Reflection"
date:   2016-11-16 19:45:31 +0530
categories: jekyll update
---

This assignment created a script that stored the answers to our previous assignment in a database. 
The database created has the names, hometowns, number of siblings, age, and favorite movies of all the respondants along with the time stamp and random string.
The first step was the set a variable for the username and to make the passwork blank. We did this with `password=''` because mysql requires a username and password.
Our script initializes mysql then creates a database called malily and then fills the database with the contents of a mysql file called *malilydab.sql*.
We then opened the database abd inserted the contents of *tblFinal*, the responses to our intial questions, into the database. 
The database then dumped into *malilydab.sql*. This circular dumping ensures that the previous responses will all be there no matter who runs the script. We also edited the script to show
the responder the database with their responses in it as well as all the previous responses. 

I learned a lot during this assignment because Malvika had experience using mysql before while I had none. 
She did a very good job of explaining what we need to do and how to do it. We worked well together to fix issues we had. 
One issue was simply with syntax problems. We researched a while before we realized that mysqldump need to be a seperate command from the rest. 
We also had a problem where the script would not work unless mysql was initialized in the terminal.
We fixed this by using the command `mysql-ctl start` at the beginning of our script. I am excited to learn more about the possible applications of this database.
It's very cool to know how to create one but since I have no experience with mysql I don't really know what the possibilities are in analyzing it now. 

Here is our (respository)[https://github.com/ldinkins/malily5.git].