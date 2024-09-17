# Overview
[![video](https://img.shields.io/badge/Demo-Video-F9D371)](https://www.youtube.com/watch?v=QA22bolC228&t=3s)
[![deployment](https://img.shields.io/badge/Deployment-Heroku-B762C1)](https://pennstagram-481b2302c61d.herokuapp.com/)

Pennstagram is a photo sharing social networking MERN app. This app allows users to upload posts publicly or keep the posts only visible to themselves. 

Pennstagram also allows users to browse other users' profile contents, like and comment photos and mention other users in a post. 

Users can follow/unfollow other users and they can get personal follower suggestions according to our recommendation rules. Session management and Security setting are also considered in our app.

## Table of Contents
* [Main Tech Stack](#main-tech-stack)
* [Features](#features)
* [Deployment](#deployment-with-heroku)
* [Remainder for Deployment](#remainder)
* [Run Locally](#Instructions-to-run-locally)
* [UI Design](#ui-design)
* [Rest API Design](#rest-api-design)
* [Demo](#demo)
* [Contributors](#contributors)
<!-- * [License](#license) -->

## Main Tech Stack
- React (Frontend)
- Express (Backend)
- Node.js (Backend)
- MongoDB (Database)

## Features
✅ User registration ✅ Login/Auth ✅ Session management ✅ Security: account lockout policy ✅ @mentions in comments

✅ Create post/Photo upload ✅ Editing/Deleting Posts (photo) & Comments ✅ Activity feed ✅ Photo likes & unliking

✅ Follow/unfollow users ✅ Follower suggestions ✅ Live updates ✅infinite scroll ✅ Privacy / Visibility control on photos

## Deployment with Heroku
https://pennstagram-481b2302c61d.herokuapp.com

## Remainder
Before you try to run the code in the localhost, you should change the env variable into 'development' mode in <mockapi.js> file. 

Before you try to deploy the app in heroku, you should change the env variable into 'production' mode in <mockapi.js> file. 

![image](https://user-images.githubusercontent.com/93689757/208328012-05916aaa-5f46-436e-a921-f2401cc5b2a5.png)

## Instructions to Run Locally
Please contact me if you want run locally:
- Ask for DB_USERNAME and DB_PASSWORD for DB connection 
- Ask for contact_your_ta_to_get_the_key and contact_your_ta_to_get_the_secret_key for AWS S3 connection 

To run the app backend:
- Open a command prompt in the "backend" folder
- Add .env file at the root and create four variables (DB_USERNAME, DB_PASSWORD, contact_your_ta_to_get_the_key and contact_your_ta_to_get_the_secret_key) in the file.
- Run the command npm install and npm start

To run the app frontend:
- Open a command prompt in the "pennstagram" folder
- Follow the instructions in [Remainder](#remainder)
- Run the command npm install and npm start
- A browser will open with the app

## UI Design
Wireframes:
- Check the wireframes for all the pages in the link below. https://www.figma.com/file/hcvBmBlkprIlLE2zYBkVXh/Wireframes?node-id=509%3A23

Prototypes:
- Successful registration (include the homepage). https://www.figma.com/file/1mJ5ntXHg8miUl6NgVg1bv/User-Story?node-id=0%3A1

- Login -> homepage -> Profile page. https://www.figma.com/file/1mJ5ntXHg8miUl6NgVg1bv/User-Story?node-id=1%3A2

- Login -> homepage -> upload a photo or a video. https://www.figma.com/file/hTUCqSL5pm1C2beY54iVTI/P3?node-id=52%3A7

- Login -> homepage -> find and follow a user -> see their activity/posts on the main activity page. https://www.figma.com/file/hcvBmBlkprIlLE2zYBkVXh/Wireframes?node-id=557%3A29

## Rest API Design
We use the MVC (Model-View-Controller) Restful architecture. Our interactive documentation of the Rest API is in the link below. https://app.swaggerhub.com/apis/cis557group32/Pennstagram/1.2.0

## Demo
The demo video is uploaded [here](https://www.youtube.com/watch?v=QA22bolC228). The demo is just for simple demonstration. It does not contain all the features we have. If you want to know more about the features, feel free to contact me.

## Contributors 
This is a group project done by myself and other two teamates.
