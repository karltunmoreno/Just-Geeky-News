# Just-Geeky-News (MVC)


This application and website is used for creating and sharing blog posts centered around a technology social site. Allows users to view, edit and delete their posts and view and comment on the posts of others. Utilizes Node.js and Express.js to create and manage a server for a blog post sharing webiste.

________________________________________________________________________________________________________________________________________________________________

###LINK
https://protected-lowlands-09239.herokuapp.com/login

_________________________________________________________________________________________________________________________________________________________________


 ![Ss](https://karltunmoreno.github.io/My-Portfolio/assets/images/Justgeekynewspic1.jpg)
 _________________________________________________________________________________________________________________________________________________________________



 ### NPM Packages:

 - **express**: High performance framework for server-side applications
 - **express-session** and **express-session-sequelize**: For session creation and to connect/sync the sequelize database to the session.
 - **mysql2 and sequelize**: To connect the application to a MySQL database and to query that database within JavaScript rather than the MySQL command-line shell.
 - **dotenv**: For setting environment variables.
 - **bcrypt**: For password hashing.
 - **express-handlebars**: For serving dynamic HTML based on database queries.

 ___________________________________________________________________________________________________________________________________________________________________

 TECH USED:

 ![JavaScript](https://img.shields.io/badge/-JavaScript-%23F7DF1C?style=flat-square&logo=javascript&logoColor=000000&color=d1b01f)

 #### Back-end:
  ![Node.js ](https://img.shields.io/badge/node.js-6DA55F?logo=node.js&logoColor=white&style=for-the-badge)
 ![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=ffffff)
   ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?logo=mysql&logoColor=white&style=for-the-badge)
   ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?logo=express&logoColor=%2361DAFB&style=for-the-badge)

 __________________________________________________________________________________________________________________________________________________________________

 ## Installation Instructions

     npm install

 ### After this repository is cloned, open your command-line in this repository's root directory to install the required dependencies denoted in the package.JSON file.

     npm start

 ### This will start the server on port 3001 for individual testing purposes. Navigate to localhost:3001/home to test the application out.

     ctrl+C

 ### Use this command to kill the server at any time.

 ## Usage Comments

 Used  HTML routes to render using handlebars. Built a CMS-style (Technology Blog).
 On the same note, used MVC for architectural structure! 
 
###OBJECTIVE

Write middleware functions for Express.js.

Use middleware to restrict access to certain routes.

Organized a codebase following the MVC paradigm.

Created templates with Handlebars.js to reduce the amount of front-end JavaScript needed.

Implemented built-in and custom helpers in Handlebars.js to help with formatting.

Store and use data saved on a back-end session.

##User Stories:

  * As a user, I can view all news articles in a list.

  * As a user, I can see how many upvotes and comments each article has.

  * As a user, I can click on the comment count to route to a different page.

  * As a user, I can visit a login page to create a new account or log into an existing account.

  * As a user, I want to stay logged in even if I refresh the page or close the browser tab.

  * As a user, I can click a "logout" button for the app to forget me.

  * As a user, I can view an article's details on a separate page.

  * As a logged-in user, I can add a comment to an article.

  * As a logged-in user, I can upvote an article.

  * As a logged-in user, I can view all of my posted articles on a separate dashboard page.

  * As a logged-in user, I can create new article posts via the dashboard.

  * As a logged-in user, I can edit or delete my existing articles via the dashboard.


