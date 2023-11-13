---
title: Pseudocode Task
description: This is a post about the pseudocode task.
date: 2023-11-13
tags:
  - projects
---
The first task was to add comments to one of the javascript tasks from a previous lesson. I chose my tip program, as I feel that the lack of front end makes it less user friendly. Comments would therefore be necessary to guide the user as to which variables could be reassigned, and which should remain the same. I decided to use single line comments, using double slashes (//) before each comment, as the comments did not need to be lengthy. I wouldn’t be commenting out any of the code, because it is all functional. Here is my code for that task, with comments added:

{% image "./tipprogrampseu.png", "My code from the tip program task, with comments added." %}

I created a new codepen file to complete task two. I wanted to do part one of the task since I am an avid reader, and a functioning program that could store my reading list would have practical applications. I decided to start small, with the six books that were currently in a pile on my coffee table. I wanted to write the basic code first, then comment it out so that I could test things such as the if/else statements. This gave me the following code:

{% image "./booklist1.png", "Array of objects." %}
{% image "./booklist2.png", "Array of objects." %}

I then added a for loop which would iterate through each book. Adding a variable called bookId allowed me to edit the output, formatting the books as ‘title’ by ‘author’. I also added an if statement and an else statement that would check the boolean value for ‘read’ and return output that would tell me whether I’d already read the book. This gave me the following code and output:

{% image "./booklistforloop.png", "The for loop I used to iterate through the book list." %}
{% image "./consoleoutput.png", "The output in the console." %}

Commenting out this code would require me to use /* and */ tags, as it is multiple lines of code. This is what it looked like:

{% image "./bookscommented.png", "My code commented out." %}

I decided to instead leave the code active, but add single line comments to explain what the code was doing. These are the comments I left:

{% image "./singlinecoms1.png", "The comments I left on the code." %}
{% image "./singlinecoms2.png", "The comments I left on the code." %}
{% image "./singlinecoms3.png", "The comments I left on the code." %}

<a href='https://codepen.io/Ellen-Furnell/pen/jOdOoJb'>Here is a link to the codepen file for the tip program.</a> <a href='https://codepen.io/Ellen-Furnell/pen/KKJqmwe'>Here is a link to my book list program.</a>