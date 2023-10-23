---
title: Tip Program
description: All about the tip program I created in Javascript.
date: 2023-10-23
tags:
  - projects
---
Heading into the tip program task, the first thing I had to do was decide what type of variable to use. I decided on let variables, as unlike const variables, their value can be reassigned. This would mean that I would be able to change values such as the total before tip, which is obviously going to be different every time. I considered using a const variable for the ‘tip amount’ and ‘total’ variables, since technically the method of calculating these amounts should be the same equation every time, but I decided against it for the time being in case I ran into a problem whilst testing the code.

I decided I needed four variables altogether: the tip percentage, which I would test at 15 percent; the pre tip total, which I would test at £30; the tip amount, which would be an equation outputting the set percentage of the pre tip total; and the final total, which would be the tip amount added to the pre tip total. I wanted the final total to be shown on the page with a sentence saying “your total, plus tip, is (amount)”. This gave me the following code:

{% image "./initialcode.png", "The initial code I wrote for this program." %}

The output on the page was:

{% image "./initialoutput.png", "Output of the code." %}

This was fine for my purposes as it showed that the code worked, but for better clarity of the end product, I wanted the value of the final total to be rounded to two decimal places. The reason for this is that £34.5 could be interpreted as £34.50 or £34.05, depending on the user’s knowledge of decimals. I used the toFixed method within the document.write function to specify that the value of the final total should be displayed to two decimal places. That gave me this code and output:

{% image "./addedtofixed.png", "My code with the toFixed method used." %}
{% image "./tofixedoutput.png", "My output with the total rounded to two decimal points." %}

I then changed the tip amount and final total variables to const variables, to reflect that these equations should not be reassigned in any way. Additionally, I added the tip amount to the output, for clarification of how much of the final total would be allocated to the tip. I also added some very basic styling to make the output of the program easier to read. That gave me the following code and output:

{% image "./addedtipamount.png", "My code with the tip amount added." %}
{% image "./styling.png", "The styling I used to make the program slightly more attractive." %}
{% image "./finaloutput.png", "The final output of my code." %}

<a href='https://codepen.io/Ellen-Furnell/pen/jOdOoJb?editors=0110'>Here is a link to the final product.</a>