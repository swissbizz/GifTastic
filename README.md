# GifTastic

Overview
In this assignment, you'll use the GIPHY API to make a dynamic web page that populates with gifs of your choice. To finish this task, you must call the GIPHY API and use JavaScript and jQuery to change the HTML of your site.

Before You Begin


Hit the GIPHY API.

Fool around with the GIPHY API. Giphy API.
Be sure to read about these GIPHY parameters (hint, hint):

q
limit
rating


Like many APIs, GIPHY requires developers to use a key to access their API data. To use the GIPHY API, you'll need a GIPHY account (don't worry, it's free!) and then obtain an API Key by creating an app.
Make sure you switch the protocol in the query URL from http to https, or the app may not work properly when deployed to Github Pages.



Watch the demo video

You should have a high-level understanding of how this assignment works before attempting to code it.




Commits
Having an active and healthy commit history on GitHub is important for your future job search. It is also extremely important for making sure your work is saved in your repository. If something breaks, committing often ensures you are able to go back to a working version of your code.


Committing often is a signal to employers that you are actively working on your code and learning.


We use the mantra “commit early and often.”  This means that when you write code that works, add it and commit it!


Numerous commits allow you to see how your app is progressing and give you a point to revert to if anything goes wrong.




Be clear and descriptive in your commit messaging.

When writing a commit message, avoid vague messages like "fixed." Be descriptive so that you and anyone else looking at your repository knows what happened with each commit.



We would like you to have well over 200 commits by graduation, so commit early and often!



Submission on BCS

Please submit both the deployed Github.io link to your homework AND the link to the Github Repository!


Instructions


Before you can make any part of your site work, you need to create an array of strings, each one related to a topic that interests you. Save it to a variable called topics.

We chose animals for our theme, but you can make a list to your own liking.



Your app should take the topics in this array and create buttons in your HTML.

Try using a loop that appends a button for each string in the array.



When the user clicks on a button, the page should grab 10 static, non-animated gif images from the GIPHY API and place them on the page.


When the user clicks one of the still GIPHY images, the gif should animate. If the user clicks the gif again, it should stop playing.


Under every gif, display its rating (PG, G, so on).

This data is provided by the GIPHY API.
Only once you get images displaying with button presses should you move on to the next step.



Add a form to your page that takes a value from a user input box and adds it to your topics array. Then make a function call that takes each topic in the array and remakes the buttons on the page.


Deploy your assignment to Github Pages.


Rejoice! You just made something really cool.




Minimum Requirements
Attempt to complete homework assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed. Adding a README.md as well as adding this homework to your portfolio are required as well and more information can be found below.
