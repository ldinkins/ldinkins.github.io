---
layout: post
title:  "Assignment Three"
date:   2016-09-27 19:45:31 +0530
categories: jekyll update
---

The work I converted was an assignment for ENEC 370 where I recorded everthing I ate for a day.
I then had to track where the food I ate came from in the world and where it was originally domesticated.
The purpose of this assignment was to make people think more carefully about their food purchases.
I then wrote a short summary of what I learned and what surprised me. 

To convert the files I created a variable FILE of my assignment in markdown format. 
Then I converted the file using "pandoc -o". This command allows you to convert between multiple formats. 
I also changed the geometry of the PDF file using "-V geometry:margin=1in" to improve the readability of the table.
This was the biggest issue I had, the table was kind of narrow and some of the titles overlapped. 
Simply expanding the margins of the PDF at first didn't help and I only had the issue with the PDF conversion.
Once I made the margin .3in though the overlap stopped and the format was much more pleasing to the eye. 

The original file I converted from was [Dinkins_assignment1.md](https://github.com/inls161/assignment-3-ldinkins/blob/master/Dinkins_assignment1.md).

**Output Files**

* [fooddiary.html](https://github.com/inls161/assignment-3-ldinkins/blob/master/fooddiary.html)
* [fooddiary.docx](https://github.com/inls161/assignment-3-ldinkins/blob/master/fooddiary.docx)
* [fooddiary.odt](https://github.com/inls161/assignment-3-ldinkins/blob/master/fooddiary.odt)
* [fooddiary.pdf](https://github.com/inls161/assignment-3-ldinkins/blob/master/fooddiary.pdf)

Here is my [editor](https://ide.c9.io/ldinkins/assignment-3) and here is my [Github script](https://github.com/inls161/assignment-3-ldinkins/blob/master/ldinkins-convert-docs.sh). 