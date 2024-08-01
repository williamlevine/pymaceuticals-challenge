# pymaceuticals-challenge

This repository contains my code for the Pymaceuticals Challenge. My code can be found in the `Pymaceuticals` folder, and is titled `pymaceuticals_working`. The source data for this challenge is also in this folder, existing as `.csv` files in a folder of their own called `data`.

The source code for this challenge is also in the `Pymaceuticals` folder, and is titled `pymaceuticals_starter`. This starter code was the grounds for most of my code, as well as the class materials from module 5.

I used ChatGPT to help debug my code, most of which involved improper use of parentheses, brackets, and so on. Where I got more help from ChatGPT was in the Summary Statistics section, where the starter code prompts for the aggregation method to generate the summary table. Here, for the standard error section, ChatGPT suggested I use the `lambda x: st.sem(x)` method, which I was unfamiliar with-- specifically the `lambda` function. I learned that this is a method which creates an anonymous function, or a function which can perform an action on a given argument in a specific situation. Here it is used as part of the `.agg` function to determine standard error.