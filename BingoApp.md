# Unit4-Project-FrontEnd

Project by:
Angelines Yaport-Garcia
Chris Nugroho
Clare Eisentrout

## https://dry-cove-26271.herokuapp.com/

*TECH STACK
=================
- Python / Django Back End
- PostgreSQL
- React App Front End
- Custom CSS

*WORK FLOW
=================
We began our workflow by brainstorming ideas and possible strategies.
We agreed early on that we would work on the set up and initial deployment together so that there were no errors or mistakes.

*PROJECT SET UP
=================
For setting up the directories we first agreed on variables to be used and who would manage the github and heroku. We then worked on getting all of the back end servers and installations working first and setting up the database, and then moved to set up the front end server and testing the database on the front end before actually coding anything out, and then set up the App.js file together to ensure everything worked as it should. Though we peer-programed this entire process, we did take turns in the process. Each of us doing a part of it while the rest gave ideas or directions. The reason for that was because we did run into A LOT of issues with getting everything working properly, especially on heroku.

*DIVISION OF WORK  
=====================
After getting the both directories set up and connected, we divided the components and each worked on a different component.
In addition to working on different components, we divided the research process for attempting and achieving our stretch goals, once we had MVP.

*PROBLEMS ENCOUNTERED
========================
Setting up all the date proved to be extremely challenging. We followed the directions to make two separate repos on GitHub before cloning the repos, but that resulted in bad file structures that were one level too deep, which caused issues when connecting to the servers, and then we weren't' sure how to connect them to each other.

In addition, though deploying to Heroku wasn't as difficult as we thought it would be (once our connection and server issues were solved that is), we ran into some major issues because we had to write a custom handleChange function to accommodate the fact that some of our form data was meant to render as a string and another part was meant to render as an array. We had to write a conditional that could handle the array input so that our data could read and parse the input. Before this conditional, we were able to see the changes happen live on the React Component console, but they would not render, so it took us a little while to figure out and solve.

We also had a few merge conflicts, nothing too crazy, which were mostly due to the mix up in file structure at first, and one or two others due to two of us trying to figure out an error on a file that one of us had worked on and accidentally made a change.

We wanted to incorporate a component that would query a third-party maps API and display local dog parks based on a user's zipcode or city name. We tried several different methods to achieve this, including the react-google-maps package, and a "Mapbox" package from Uber. Neither of these packages was easy for us to understand, and neither seemed designed to produce the component we wanted. Eventually, we decided to build something from scratch.

*HOW PROBLEMS WERE FIXED
===========================
We fixed the issues encoutered by doing reasearch and looking at the console, terminal, and React Components console. We also posted messages in the sos channel and asked some of our peers. However, we are actually  quite proud of ourselves because though we received some help from our peers, we were able to solve most of the issue on our own and actually learned from them.

We also learned more about fixing merge conflicts and how to deal with them, as well as how to improve our team working skills and communication.

##Integrating Google Maps

We ran into a lot of issues rendering a dynamic map that would update based on the state of the component. Eventually, what worked was the following:

- We used the Embed Google Maps Quickstart page to generate a URL that would show "dog parks near Boston, MA".
- Once we had this URL, we were able write a component method that would interpolate user input (in the form of a zipcode or a city name) into a variable called "localMapUrl", replacing the "Boston, MA" parameters.
- Finally, the method updates the state of the Map component to reflect the localMapUrl in the rendered iframe src attribute. A dynamic map!

*WHAT WENT WELL
====================
Despite the merge conflicts, we actually kept good communication and talked everything out. Even when pushing and pulling and doing anything at all, we let each other know what each of us would do and if we were pushing or pulling something, as well as agreeing when to actually push and pull.

As mentioned before, we feel that we were able to learn from this experience and from each error we came across. We may not remember each one specifically from the top of our heads, but will most likely recognize it and figure out how to fix it if it happened again.

*WHAT DIDN'T GO WELL
=======================
Needles to say, all the setting up did not go well at all. It took us almost two days to finally get the set up done and deployed correctly. We had to reorganize our files structure and move things around.
We felt that it was just taking too long to get it done and began to worry about falling behind.
Thankfully, we were able to figure it out before lunch on the second day.

*WHAT WOULD HAVE BEEN IMPROVED IF HAD MORE TIME
=================================================

- We are very aware of how much thought can and should go into database design! Even something as simple as wanting to change one of our model's fields from "IntegerField" to a field that accepts decimals feels like a lot of backtracking. Would this invalidate all the data we'd already built?
- We would consider some front end design elements differently, like incorporating the weather and map information into one component that would only require the user to enter their zip code once.
- We were unsure of how to navigate some privacy issues with API keys getting pushed to GitHub.

*WIREFRAMES
============

![AdobeXD Wireframe](https://i.imgur.com/RYhVid6.jpg)
![Paper Mobile Wireframe](https://i.imgur.com/br50xOZ.jpg)
![Paper Tablet Wireframe](https://i.imgur.com/Nw1oGTK.jpg)
![Paper Desktop Wireframe](https://i.imgur.com/3K6Yc8X.jpg)
