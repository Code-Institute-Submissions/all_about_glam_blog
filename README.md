# [All About Glam]() - Milestone Project : Data Centric Development - Code Institute 

## Table Of Content 

- [**About**](#About)
  - [**Why This Project?**](#Why-This-Project?)
- [**UX**](#UX)
  - [**User Stories**](#User-Stories)
  - [**Research**](#Research)
  - [**Wireframes**](#Wireframes)
  - [**Design**](#Design)
- [**Features**](#Features)
  - [**Functionality**](#Functionality)
  - [**Existing Feautures**](#Existing-Features)
  - [**Features Left To Implement**](#Features-Left-To-Implement)
- [**Technologies Used**](#Technologies-Used)
  - [**Languages**](#Languages)
  - [**Tools**](#Tools)
  - [**Libraries**](#Libraries)
  - [**Frameworks**](#Frameworks)
  - [**Hosting**](#Hosting)
- [**Testing**](#Testing)
  - [**Browesers And Divices**](#Browesers-And-Divices)
  - [**Testing User Stories**](#Testing-User-Stories)
  - [**Resolved Bugs**](#Resolved-Bugs)
  - [**Unresolved Bugs**](#Unresolved-Bugs)
  - [**Code Validation**](#Code-Validation)
- [**Deployment**](#Deployment)
- [**Credits**](#Credits)
  - [**Content**](#Content)
  - [**Acknowledgements**](#Acknowledgements)
  - [**Media**](#Media)
  - [**Disclaimer**](#Disclaimer)  


## About
This application is a blogpost and it was created for users to get inspired and share anything related to beauty. Users can create an account where they can add as many blogposts as they like for free! Plus they can update or edit their posts and profile account. 

## Why This Project?
This application was created for my 3rd Project with Data Centric Development for [Code Institute](https://codeinstitute.net/). I used Python and a no-SQL database, MongoDB, to create this project which uses CRUD operations to allow users to create, read, update and delete their posts.

## UX

### User Stories
* As a user, I want to be able to create my own account.
* As a user, I want to be able to log in and out of my account.
* As a user, I want to be able to create a blog post.
* As a user, I want to read inspiring posts from the web application.
* As a user, I want to be able to edit and update my blog posts.
* As a user, I want to be able to edit my profile account.
* As a user, I want to be able to delete my blog posts.
* As a user, I want to be able to my profile account.

### Research
I researched tutorials with Python and MongoDB on Youtube and Udemy, to understand more how to create a CRUD application and I could get a clear idea of what functionality and design I wanted my web application to have, however most of this project's user authentication functionality was taken from [Code Institute's](https://codeinstitute.net/) task manager mini project.

### Wireframes
To create this project's wireframes I used [Balsamiq](https://balsamiq.com/).

During the development process some changes were made

### Design
I wanted a pink color scheme for this project to give a girly and fun look. For the background I used a glittery fuchsia image and I kept the color of the navbar, footer and buttons the same color of light pink. All form have a white background with black text and icons. 

## Features

### Functionality
The web application uses Python login to allow user to register or login to their account for free and in addition it offers CRUD operations which allows users to create, read, update and delete their posts or profile account.

### Existing Features
* Register 
 Users can create their own account for free by filling the form and providing a username, email address and password which are stored in the database. The Form cannot be submitted if the username already exists or the email address has already been used. The users have to repeat their password to ensure there are no mistakes. The users passwords are hashed for security purposes.
* Login 
The login form has a username and password field which if correctly put in the users can login in their account.
* Logout 
Users can logout of their account by clicking "Logout" in the navbar. 
* Users Profile
Users who are logged in can visit their profile page and view their personal information. Users are also allowed to edit or delete their profile.
* NavBar
The navbar link vary depending on whether the user is logged in or not. If the user is logged in, the navbar will have Home, Profile, Create Post and Logout links. If the user is logged out, the navbar will have Home, Register and Login links.


### Features Left To Implement 

## Technologies Used 

### Languages 
1. [HTML](https://en.wikipedia.org/wiki/HTML)

HTML was used in this project to keep up with the latest industry standards. 

2. [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

CSS was used for styling the content.

3. [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

JavaScript was used to create the main functional logic of this app. 

4. [Python](https://en.wikipedia.org/wiki/Python_programming_language)

Python was used as the back-end programming language for this app.

### Tools 
1. [Git](https://git-scm.com/)

Git was used in this project for version control.

2. [Gitpod](https://www.gitpod.io/)

Gitpod was used to develop this project.

3. [Balsamiq](https://balsamiq.com/)

Balsamiq was used to create the wireframes.

4. [Dev Tools](https://developers.google.com/web/tools/chrome-devtools)

Chrome DevTools is a set of web developer tools built directly into the Google Chrome browser. DevTools can help you edit pages on-the-fly and diagnose problems quickly, which ultimately helps you build better websites, faster. Google Chrome's Dev Tools was used in the building process of this project.

### Libraries 
1. Icons were obtained from [Font Awesome](https://fontawesome.com/).

2. Fonts were taken from [Google Fonts](https://fonts.google.com/).

3. [Materialize](https://materializecss.com/)

Materialize UI components help in constructing attractive, consistent, and functional web pages and web apps, while adhering to modern web design principles such as browser portability, device independence, and graceful degradation.

### Frameworks 
1. [jQuery](https://jquery.com/)

jQuery is a fast, small, and feature-rich JavaScript library. It was used in this project to simplify the DOM.

2. [Flask](https://flask.palletsprojects.com/en/1.1.x/)

Flask is a micro web framework written in Python. 


### Hosting 
* [Heroku](https://www.heroku.com/)

Heroku was used as the hosting platform to deploy this app.

## Testing

## Deployment 

## Credits 

### Media 

### Acknowledgements

### Disclaimer
This project is for educational purposes only.
