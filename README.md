#Week 13 Assignment
##Friend Finder

![alt tag](https://github.com/winniemlau/friendFinder/blob/master/app/assets/images/screenshot.png)

###Objective

* Build a compatibility-based "Friend Finder" application. (Basically a dating app)
* The application will take in results from users' surveys then compare their results against all other users who have completed it. The application will then display the name and picture of the user with the best match overall.
* Use Express to handle routing and will deploy your application on Heroku so others can fill it out.

###Technologies

* HTML
* CSS
* Javascript
* Node.js
* Express.js
* Body-parser
* Path

###App Functionality

* The survey consists of 10 questions. Answers to the survey questions should be on a scale of 1-5 based on how much the user agrees or disagrees.
* Data in the application should be saved as an array of objects.
* Compatibility should be determined based on the following:
1. Each user's results should be converted into a simple array of numbers (ex: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]).
2. There will be a difference between the user's scores against other users' scores, question by question. App will add up the differences to calculate the totalDifference.
Example:
User 1: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]
User 2: [3, 2, 6, 4, 5, 1, 2, 5, 4, 1]
Total Difference: 2 + 1 + 2 = 5
* Once the closest match has been determined, it will display in the form of a modal pop-up.
* The result should display both the name and picture of the closest match.
