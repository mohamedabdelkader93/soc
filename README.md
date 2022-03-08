 
 <div align="center">

 # socialApp
[![](https://img.shields.io/badge/Made_with-Nodejs-red?style=for-the-badge&logo=node.js)](https://nodejs.org/en/)
 [![](https://img.shields.io/badge/Made_with-ReactJS-blue?style=for-the-badge&logo=react)](https://reactjs.org/docs/getting-started.html)
[![](https://img.shields.io/badge/Database-MongoDB-red?style=for-the-badge&logo=mongodb)](mongodb.com "MongoDB")
[![](https://img.shields.io/badge/IDE-Visual_Studio_Code-red?style=for-the-badge&logo=visual-studio-code)](https://code.visualstudio.com/  "Visual Studio Code")
[![](https://img.shields.io/badge/Deployed_on-Heroku-red?style=for-the-badge&logo=heroku)](https://www.heroku.com/  "Heroku")
</div>

A Social Networking web app similar to Instagram.

## Deployed website

[https://sociallappp.herokuapp.com/](https://sociallappp.herokuapp.com/)

## Features

* SignUp / SignIn.
* Forgot password.
* Google Oauth Login.
* edit / delete your profile.
* Follow / Unfollow users.
* create / edit / delete posts.
* create / delete comments.
* Like / Unlike posts.
* Personal chat with users.

## Demo 

<div align="center">

<h4 align="center">Home Page</h4>
<img src="./demo/home.PNG" width=900px/>
<br>
<h4 align="center">Comments</h4>
<img src="./demo/comments.PNG" width=900px/>
<br>
<h4 align="center">Profile Page</h4>
<img src="./demo/profile.png" width=900px/>
<br>
<h4 align="center">Confirm</h4>
<img src="./demo/confirm.PNG" width=900px/>
<br>
<h4 align="center">Chat</h4>

![demovideo](./demo/chat.gif)
<br>
<h4 align="center">Reset Password</h4>
<img src="./demo/resetpassword.PNG" width=900px/>
<br>


</div>

## To run the project locally

* clone this Repository by `git clone https://github.com/shahshubh/socialApp-MERN.git`.
* Inside /server directory create a .env file and add these
    - `MONGO_URI=your-mongodb-url`
    - `PORT=8080`
    - `JWT_SECRET=any-random-string-of-any-length`
    - `CLIENT_URL=http://localhost:3000`
* Inside /client directory create a .env file and add
    - `REACT_APP_API_URL=http://localhost:8080`
* Change the directory to /server in the terminal and run:
    - `npm install`
    - `node app.js`
* Change the directory to /client in the terminal and run:
    - `npm install`
    - `npm start`
* Open your browser and enter url `http://localhost:3000`

## Tech Stack of this Project

* Frontend: Reactjs, Bootstrap Material
* Backend: Nodejs
* Framework: Expressjs
* Database: MongoDB

<!-- 
## Further Work

- [ ] Improve performancem - decrease loading time.
- [ ] Display status of users online/offline in chat.
- [ ] Add Notifications when someone follows/messages you or likes/comments on your post.  -->


