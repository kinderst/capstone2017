# Health Nuts
*envision nutrition*

Welcome to the HealthNuts Project Repository.

This website is not deployed on the web due to possible security issues and no budget to pay for API plans.
Instead, you can see a demo of the current version of this product at:
youtube.com

## List of Contents
1. Overview
2. Necessary Technology Needs
3. Currently Chosen Resources to Meet Those Needs
4. Firebase
5. React
6. Clarifai
7. Nutritionix
8. Stack
9. Contact Information

## 1. Overview
(Cory do overview of project here)

## 2. Necessary Technology Needs
To complete this project, we need the following things:
1. A way to deploy the application

   The website must be able to be run somehow and eventually be hosted on a public web server
   
2. A simple database and file storage system

   We just need to be able to have users, upload photos, and store some information about the photos users upload, a couple other small things.
   
3. A JavaScript Framework to handle the complexity and nuiance of the functionality that we require.

   Single there will be multiple, connected pages with all sorts of things happening on the front end, we need a framework that can not make our normal js code look like soup.
   
4. A way to detect what sorts of foods are in an image

   Since once of our project aims is to make the food journaling process more efficient, we need a way to not make users have to write down all the specific food items but rather the technology should just know by now whats in the photo, it's 2017.
   
5. A way to determine what sort of nutritional substance makes up a given food item

   We don't just want to know what foods you ate, we also want to know what the nutritional value of the food you just ate is!
   
## 3. Currently Chosen Resources to Meet Those Needs
To accomodate our project needs, we chose the following resources:
1. Node.js

   We chose to use Node.js since we also chose to use React, and React deploys with Node. See Node documentation here: https://nodejs.org/en/ 
   
2. Firebase

   Google's popular client-side Firebase actually perfectly accomodates all of our needs. Firebase takes care of user information, including email handling, password managing, persistent log in, file storage system, and a NoSQL database which we can model in such a way that we can store information about users, their photos, and the information about those photos.
   
3. React

   Facebook also released a very well made product that makes websites very, very fast. It also uses components to make code more reusable. We can also dynamically render views, save, change, and pass states between pages, and more! This makes for a very useful framework for us to use.
   
4. Clarifai

   Clarifai's magic API allows us to send it an image, and get back results of all the items it thinks it sees in the food. They allow for a free version which is extremely limited in requests, but will allow for testing purposes, and can always be upgraded.
   
5. Nutritionix

   Nutritionix is a relatively simple API that allows you to send it a query of a food item, and it returns like-name based results and some nutrient values. We are considering changing this, but for now it works relatively well, but there are limitations.

## 4. Firebase
Firebase is

## 8. Stack
Our stack is one that is not really commonly defined but technically it would be: FERN.

The "F" stands for Firebase, that is our client-side database. It doesn't need to be server side, because it can query the database and return json, and google handles all of the user/password authentication.

The "E" stands for ExpressJs/ES6, which is pretty much just necessary for React. See documentation for ES6 here: https://github.com/developit/express-es6-rest-api 

The "R" stands for React, which is a powerful js framework that helps create robust web applications and keep the code managable.

The "N" stands for Node.js which is JavaScript runtime to allow web apps to be deployed easily. See documentation for Node here: https://nodejs.org/en/ 

This stack allows us to be really light-weight and dynamic by not having to worry about
having a backend. The React framework allows us to do really powerful things like
easily load modules to solvw a lot of common problems, such as connecting to 
firebase, etc. It also was created by Facebook and therefore is very very fast
as it caches components which are the rendered dynamically to the page. We do
not need to have a complicated, highly structured backend to accompolish this
project, we really only need users, photos, and some information about the
photos users upload, and a bit more but not much.
