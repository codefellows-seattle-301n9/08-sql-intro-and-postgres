# 08-sql-intro-and-postgres

**Author**: Brandon Buchholz, Mitch Hall
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->

This application serves a blog site that allows users to see currently published articles. It also serves a NEW.html page that will allow new articles to be published by joining a local server to a local database.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
In Terminal: run > nodemon server.js In web browser: > load localhost:3000 /index.html || /new.html

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
This application uses HTML, CSS, Javascript(with the jQuery library) and Node.js (with Express and nodemon)


## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples: -->

Thu Dec 21 21:33:17 2017 -0800- brandon performed a npm install, confirmed page loads, switched the code database for a mac user, answered comment that has to do with line 33 of server.js

Thu Dec 21 20:52:06 2017 -0800- setup project with npm init - installed required packages, setup link for postgres database, removed two lines of code that dealt with saving to local JSON file, passed the appropriate argument into the function that instantiates a new pg.Client - switching drivers


## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
Jb Tellez, instructor  TA's Michael, Madeline, James