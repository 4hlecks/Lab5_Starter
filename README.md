# Lab 5 - Starter
Alex Atienza

**PLEASE NOTE**
There is a bunch of freaking weird pull requests and stuff and the node_modules folder is showing because I made this before you updated the main.yml box so I could not figure out for the love of god why my unit tests weren't working so I took out the .gitignore for node_modules/ and then it started working, then I refreshed the lab writeup to see that the main.yml box was updated so I was just going back and forth deleting and installing stuff because the github pages wasn't loading so please please please I swear I did all the steps correctly and in order.

**1. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.**


I don't think I would use a unit test to test the "message" feature of a messaging application. This is because unit testing is meant for testing individual parts of your code and debugging on a smaller scale. I think the "message" feature is a broad feature of a messaging application and includes a lot of sub-features which also have sub-features, then and there is when you should do unit-testing.


**2. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.**


I do think I would use a unit test to test the "max message length" feature of a messaging application because it is a smaller scale feature that can be debugged with a unit test. There are no other factors to test besides the character limit of 80 so it would be quite simple to test, which is the point of the unit test.


**Link to Github Pages Site**

https://4hlecks.github.io/Lab5_Starter/expose.html
https://4hlecks.github.io/Lab5_Starter/explore.html
