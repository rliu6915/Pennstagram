# Overview
Pennstagram is a photo sharing social networking MERN app created in 2022. This app allows users to upload posts publicly or keep the posts only visible to themselves. As a social networking app, Pennstagram also allows users to browse other users' profile contents, like and comment photos and mention other users in a post. Users can follow/unfollow other users and they can get personal follower suggestions according to our recommendation rules. Session management and Security setting are also considered in our app.

# Features
✅ User registration ✅ Login/Auth ✅ Session management ✅ Security: account lockout policy ✅ @mentions in comments

✅ Create post/Photo upload ✅ Editing/Deleting Posts (photo) & Comments ✅ Activity feed ✅ Photo likes & unliking

✅ Follow/unfollow users ✅ Follower suggestions ✅ Live updates ✅infinite scroll ✅ Privacy / Visibility control on photos

# Deployment with Heroku
https://pennstagram.herokuapp.com

# Contributors 
This is a group project done by myself and other two teamates.

# Remainder: 
Before you try to run the code in the localhost, you should change the env variable into 'development' mode in <mockapi.js> file. 

Before you try to deploy the app in heroku, you should change the env variable into 'production' mode in <mockapi.js> file. 

![image](https://user-images.githubusercontent.com/93689757/208328012-05916aaa-5f46-436e-a921-f2401cc5b2a5.png)

# UI Design:
Wireframes
Check the wireframes for all the pages in the link below. https://www.figma.com/file/hcvBmBlkprIlLE2zYBkVXh/Wireframes?node-id=509%3A23
Prototype

1. Successful registration (include the homepage). https://www.figma.com/file/1mJ5ntXHg8miUl6NgVg1bv/User-Story?node-id=0%3A1

2. Login -> homepage -> Profile page. https://www.figma.com/file/1mJ5ntXHg8miUl6NgVg1bv/User-Story?node-id=1%3A2

3. Login -> homepage -> upload a photo or a video. https://www.figma.com/file/hTUCqSL5pm1C2beY54iVTI/P3?node-id=52%3A7

4. Login -> homepage -> find and follow a user -> see their activity/posts on the main activity page. https://www.figma.com/file/hcvBmBlkprIlLE2zYBkVXh/Wireframes?node-id=557%3A29

# Rest API Design:
We use the MVC (Model-View-Controller) Restful architecture. Our interactive documentation of the Rest API is in the link below.

https://app.swaggerhub.com/apis/cis557group32/Pennstagram/1.2.0


# Instructions
To run the app locally, follow these steps:

1. Open a command prompt in the "backend" folder
2. Run the command npm start
3. Open a command prompt in the "pennstagram" folder
4. Run the command npm start
5. A browser will open with the app
