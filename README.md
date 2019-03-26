# GA Project 3 : A MERN Stack App - Group Project

### Timeframe
7 days

## Technologies used

* JavaScript (ES6), React, Node.js, Express
* HTML5, SCSS, Bulma
* MongoDB, Mongoose, JSON
* Yarn, Babel, Webpack
* BCrypt, oAuth
* Heroku, GitHub/Git
* Chai

## APIs
* FileStack
* Mapbox

## Contributors
* This was a group project with 4 members. The project was managed using Trello and daily stand-ups.

## Installation

1. Set up a project repo by a git master
2. Clone the repo
3. Created basic the back-end and front-end files
4. Set up Webpack and installed all the dependencies packages
5. Set up and run the server
6. Open the `index.html` in browser
8. Deployed on Heroku

### App overview - 'Hidden Gems'

<img width="301" alt="Screenshot 2019-03-26 at 21 32 01" src="https://user-images.githubusercontent.com/42609274/55036245-f06f4180-5011-11e9-80d9-cca6b5aa7215.png">

The Hidden Gem app allows users to look for landmarks or any other places of interest, also referred as 'Gems' on the website. The user can also add their own 'Gems' or create 'Trips' using a collection of 'Gems'. The concept of the app is to allow users to share unique places that they've been to and for others to find these places and experience it for themselves.

Key features of the App are being able to follow other users. Navigation to a Gem from user's location to the gem via using google maps.

You can find a hosted version at https://wdi-hidden-gems-project-3.herokuapp.com


### Users and sessions
The users can register on Hidden Gems through Register Page and Sign In through Login Page. The users must be logged in to add new gems, create new trip to the database and follow other users.

Signed in users can access their Profile page. From here they can see the number of gems and trips they have uploaded and the users they follow. User profile images are uploaded using FileStack, but the FileStack API key last for 15 days therefore, I've taken it off.

<img width="1271" alt="Screenshot 2019-03-26 at 21 51 37" src="https://user-images.githubusercontent.com/42609274/55036049-62935680-5011-11e9-98ab-8eb6662d5ab6.png">
<img width="1271" alt="Screenshot 2019-03-26 at 22 38 52" src="https://user-images.githubusercontent.com/42609274/55038198-fa943e80-5017-11e9-993e-e0fd38b191ce.png">

### Gems
You can view all Gems on the index page and search by category or city. Clicking on a Gem will take you it's show page. Gems are uploaded by a user and can also belong to several Trips.

<img width="1259" alt="Screenshot 2019-03-26 at 22 44 15" src="https://user-images.githubusercontent.com/42609274/55038801-f5d08a00-5019-11e9-8776-2090608fcd71.png">


The Gem show page includes a description, gem's location on a map, comments, name of user who uploaded the gem and list of trips in which the gems has been added to.

<img width="1266" alt="Screenshot 2019-03-26 at 22 50 28" src="https://user-images.githubusercontent.com/42609274/55038697-9d00f180-5019-11e9-8bb7-3c4cf968ea00.png">


### Trips

The Trips section encourages users to explore Gems and incorporate the Gems on their Trip. Signed-in users can create a Trip to complete. A Trip is comprised of a collection of gems and displayed on the map.

<img width="1053" alt="Screenshot 2019-03-26 at 23 07 03" src="https://user-images.githubusercontent.com/42609274/55039399-e6524080-501b-11e9-93bb-a8c05c5e4c16.png">


## Process

The development process started with wireframes to implement the user's journey and basic functionality of the site. We then decided the structure of the database and routes. Once our models were build for our database, we started working on setting up controllers for all routes. The api routes were then tested by making requests with Insomnia.  


Making use of git we carried out individual work on branches for each feature. This was merged with the Development branch and any merge conflicts were fixed as a group. Prior to pushing the code to the Master branch, features were tested on the Development branch

Tasks were managed and assigned through the task manager Trello. We performed daily stand-ups to keep track of progress.


<img width="1275" alt="Screenshot 2019-03-26 at 23 31 05" src="https://user-images.githubusercontent.com/42609274/55040204-472f4800-501f-11e9-98d8-fbb69d36c562.png">

### Challenges


### Wins



## Future features
