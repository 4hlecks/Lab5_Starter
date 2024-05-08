# Lab 5 - Starter
Alex Atienza

Can Yavuz

**PLEASE NOTE**

There is a bunch of weird pull requests and stuff because towards the end of the lab, I couldn't figure out why my unit tests weren't passing even though they were supposed to pass and it was because the dependencies weren't there, but the write up said to include node_modules/ in the .gitignore. I didn't know hours in you guys updated the lab-writeup to update the main.yml and I never refreshed the page so I was stuck for a while and ended up doing npm install and pushing that directory. Then, I was worried mt github pages wouldn't load without the dependencies but I clarified in the lab-5 channel on slack if we didn't need it, you can check too. So today I just deleted the node_modules directory. So it was a lot of back and forth steps but I promise I did all the steps originally in order.

**1. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.**


I don't think I would use a unit test to test the "message" feature of a messaging application. This is because unit testing is meant for testing individual parts of your code and debugging on a smaller scale. I think the "message" feature is a broad feature of a messaging application and includes a lot of sub-features which also have sub-features, then and there is when you should do unit-testing.


**2. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.**


I do think I would use a unit test to test the "max message length" feature of a messaging application because it is a smaller scale feature that can be debugged with a unit test. There are no other factors to test besides the character limit of 80 so it would be quite simple to test, which is the point of the unit test.


**Link to Github Pages Site**

https://4hlecks.github.io/Lab5_Starter/expose.html

https://4hlecks.github.io/Lab5_Starter/explore.html
