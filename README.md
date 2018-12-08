# brocal

## Overview:

 - Simple application using the following frameworks: HTML, CSS (Materialize), JS and MySQL database for the front end.
 - The application uses Node.js (and node modules), Express.js and Express-handlebars. The Node modules used were the following: authentication – Passport.js. In addition, we used ORM – Sequelize and finally, we used several API’s, which are the following: Nutritionix, myfitnesspal, GET/READ/POST/DELETE.
- - -

## App Details:

- BroCal is a fitness application that allows users to input and track information such as weight, food, fitness, etc.
- User will be able to register an account login with username and password.

## AWS Details

This project was ported to run seamless on AWS, inspired by AWS modern Application workshop.  

[https://github.com/aws-samples/aws-modern-application-workshop](https://github.com/aws-samples/aws-modern-application-workshop "Modern Application Workshop")

- - -

## App Functionality Overview 

Account creation (POST – Database)

1. Email
2. Name
3. Password

User Login (POST – Database – Authorization)

User information – Create profile
- First login – POST – Database

Attributes (age, height, weight, sex, weight goals)

- User information – Active user
- Login – (POST – Database – Session Logging/ User Authentication)

Homepage – dashboard display
    a.	Graphs
      i.	Calorie intake – daily/weekly
      ii.	Goal weight – progress based on weekly/monthly/annually
      iii.	Food/alcohol info
   b.	Menu bar – bottom
      i.	Dashboard – button
      ii.	Track – food/alcohol
      iii.	Forms – modal
Food
   a.	Food name
   b.	Servings
   c.	Meal category
   d.	Calories
Alcohol
  a.	Alcohol name
  b.	Servings
  c.	Alcohol category
  d.	Calories
    iv.	Track – weight
1.	Forms – modal
   a.	Current weight
   b.	Feels 
    c.	Preferences (placeholders until app works)
2.	Menu bar – top
    a.	App name
    b.	Profile information
    c.	Alerts – notifications

- - -
### Minimum Requirements

Current versions of

|Tech | Runtime |
|-----|-----|
|OS | Linux or Mac|
|Languanges | NodeJS|
|Database | MySQL|

- - -
### Instructions

1. Clone the repo.
2. From the newly cloned BroCal directory, install required dependencies
3. Start node app.
4. Open your browser and go to: *http://localhost:3000/*
