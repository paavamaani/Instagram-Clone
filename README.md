# Instagram Clone

<p> Instagram clone is a social media platform that aims to recreate the functionality and user experience of Instagram. It allows users to share pictures and videos, apply filters and effects, and connect with friends and followers. The platform typically includes features such as a feed for viewing content, a profile for showcasing your own content, the ability to like and comment on posts, and a search function for discovering new users and content. Which is deployed in the AWS Elastic Compute Cloud (EC2) environment and is equipped with an autoscaling load balancer to manage high traffic demands </p>

<img src="https://www.movilzona.es/app/uploads-movilzona.es/2018/01/GIF-en-Instagram-1.png">

## Tech Stack
<p align="left"> 
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://redux.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> 
</p>

## System Architecture

### Frontend

- React JS
- Redux

### Backend

- Node JS
- Express JS

### Database

- MongoDB
- MySQL

### Deployment

- AWS EC2

## Object Management Policy

When a request is made from the client, the request is processed by the API gateway, and the request, along with its parameters like path params, query params and body params are extracted and forwarded to Node JS. Once the request task is accomplished, the response is sent to client. 

## Handling heavyweight resources

*	The server's load was distributed and handled via load balancing to multiple instances of our application.

## Steps to run the application

1. git clone [repo](https://github.com/paavamaani/Instagram-Clone.git)
2. Install dependencies npm install ```npm install```
3. Run - ```npm start```

## Screenshots of the App

<img src="./images/login.png">
<img src="./images/home.png">
<img src="./images/story.png">
<img src="./images/chat.png">
<img src="./images/explore.png">
<img src="./images/profile.png">
