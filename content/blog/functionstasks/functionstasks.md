---
title: Learning Functions in Javascript
description: Completion of the functions tasks for my assignment.
date: 2023-10-25
tags:
  - projects
---
For Task 1, I decided to output the simple sentence “My name is Ellen.” Setting the function to display this sentence on the document whenever it was invoked was a simple process; I used the document write function. Here is my code and output:
{% image "./task1code.png", "My code from the first task." %}
{% image "./task1output.png", "The output of my code." %}

Task 2 required me to combine a first and last name inside a function. I decided to set the first and last name as let variables, and concatenate them inside the function, outputting this information using document.write. I also added line breaks for ease of comprehension. Here is my code and output:
{% image "./task2code.png", "My code from the second task." %}
{% image "./task2output.png", "The output; my name." %}

To have the function accept my name as an argument, I had to create a variable that would store my name as arguments, as well as printing my name with this new format. Here is what the resulting code and output looked like:
{% image "./task2arg.png", "My code from the second task with arguments." %}
{% image "./task2argoutput.png", "The output of adding arguments to my code." %}

For Task 3, I then declared two variables within my combineName function and set a return statement to return the value of the variables multiplied. This was my code:

{% image "./task3code.png", "My code from task 3." %}

Task 4 required me to create a program that would tell me what to wear based on the outside temperature. I created a let variable named ‘temperature’ and decided to test it at 35 degrees to begin with. If/else statements seemed to be the best way to set up this program, as I would be using few conditionals: one ‘if’ statement, two ‘else if’ statements, and one ‘else’ statement. I decided to add the logical operator <= (less than or equal to) for each condition, to make sure to specify what should happen if the temperature is equal to one of those specified in the if/else statements. This was my resulting code and output:

{% image "./task4code.png", "My code from task 4." %}
{% image "./task4output.png", "My output from task 4." %}

Since I was testing the temperature at 35, an amount that is less than 50, this was the correct output. Next I tested the temperature at -7 degrees, to double check that my code was working correctly:

{% image "./task4testing.png", "Testing the temperature task with the variable changed to -7." %}

<a href='https://codepen.io/Ellen-Furnell/pen/oNmNKqx?editors=0010'>Here is a link to the codepen where I completed these tasks.</a>