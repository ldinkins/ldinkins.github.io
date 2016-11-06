---
layout: post
title:  "Assignment Four Reflection"
date:   2016-11-06 19:45:31 +0530
categories: jekyll update
---

Malvika and I worked on the first part of the assignment together in class. We created a list of questions getting to know some personal information about about the respondent. 
Creating the script to ask the questions was relatively easy. We struggled a little with the random string generator but it turned out we were just copying the code incorrectly. 
At first we tried to create a function that would give the date stamp but this proved unsucessful. While working individually Malvika realized that our function was producing the date for the wrong time zone. 
She found a simpler code. One thing I was confused about while writing our script is why we had to `echo` the variables into the csv file. Would it have worked the same to have `$name,$hometown,$siblings,$age,$movie,$generator,$datestamp >> final.csv`?
We also originally had a script that overode each answer in the `final.csv` file but we realized we needed double greater than symbols. 
Malvika worked on a bonus section creating a function that prints the final.csv file if the respondant wants to see it. I then created a branch to try to add colors to the questions and responses. 
I wanted to add some color to our questionare and to the results.
I tried many codes unsucessfully before realizing how easy it was to set a color to be equal to a variable and then apply it. I found my information from this [website](http://stackoverflow.com/questions/5947742/how-to-change-the-output-color-of-echo-in-linux).
I was getting very frustrated until I noticed I had forgotten to add the `-e` after `echo`.

![oops](https://media.tenor.co/images/20ac0577cc7b851e51034ef1a6eefdab/raw)

I really enjoyed working in a group project. I think it helped me learn a lot and made me more accountable for my work.
We only had one issue pushing and pulling our commits. Somehow a change had been made to the `final.csv` file at the same time. 
I resolved this issue by readding the modified file and then committing and pushing the changes. 
It was a quick fix but we both got stressed out because of how many error messages it gave us! 

Here is the link to [our repository](https://github.com/ldinkins/malily-assignment-4). 

