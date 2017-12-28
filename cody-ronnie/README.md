# SQL INTRODUCTION

**Author**: Cody Green - Ronnie Lewis
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
As a user, I want to store my articles in a database so that my articles are available for users from an external source.

Install and require the NPM PostgreSQL package pg in your server.js file.
Make sure to complete the connection string.
Windows and Linux users: You should have retained the user/password from the pre-work for this course. Your OS may require that your connection string is composed of additional information including user and password. For example: const conString = 'postgres://USER:PASSWORD@HOST:PORT/DBNAME';
Mac users: const conString = 'postgres://localhost:5432';
Pass the appropriate argument when instantiating a new Client.
The articleView.js methods are different now that we are not accessing the JSON file directly, and instead retrieving the articles from a database. Therefore, we no longer need to export the JSON, so remove all code that was involved in performing this action.
As a developer, I want to review my code base so that I have a deep understanding of its overall functionality.

Study each of the new routes in your server.js file by examining the SQL statements and any associated data being handed through the request.
For each of the COMMENT items in server.js, provide a brief description of what that function immediately below is doing. Be sure to indicate, where applicable, details such as:
What number(s) of the full-stack-diagram.png image is this part of the code interacting with?
Which method of article.js is interacting with this particular piece of server.js?
What part of CRUD is being enacted/managed by this particular piece of code?
As applicable, an additional sentence or two of explanation about what the code is doing, what NPM packages are involved, etc. The goal is to demonstrate that you understand what is going on in the code without glossing over details, but also without writing a novel about it.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
first you would clone the REPO to your local machine and then follow the problem domain.

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
the whole application uses jquery, javascript, html, css, JSON, as well as SQL 

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:
12/27/2017 7:15pm finished the comments and preparing for submit
## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
-->
my partner Ronnie and the png file listed here [link to png](https://github.com/codyjgreen/08-sql-intro-and-postgres/blob/master/full-stack-diagram.png)
