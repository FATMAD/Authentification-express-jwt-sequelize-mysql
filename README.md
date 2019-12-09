# Authentification-express-jwt-sequelize-mysql
Basics of Authentication using Passport and JWT with Sequelize and MySQL Database

Hello there, welcome to my first medium post.
It so happened that I was looking for resources to guide me as a beginner with NodeJS, how I can implement JWT to authenticate a user using MySQL database with Sequelize. So after surfing the internet for a while, I was able to come across some useful resources like this and a bunch of others, I’m still new to back-end, so it was a bit stressful to combine all the pieces together.
I thought I should put together all these pieces, to help someone who is also struggling with it or would soon start to look for it just like I was.
Before we dive in, let’s explain what each of these technologies are.
Passport is authentication middleware for Node.js. extremely flexible and modular.
JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
Sequelize is a promise-based Object Relational Mapping for Node.js.
Disclaimer: This post is introduction and is focused at someone that just want to see how these technologies work together.
You need to have Node.js installed on your computer and also Postman or any tool that can be used to test requests. All steps that would be shown here were performed on Windows OS.
We are going to create a simple project, very simple
