
FULLSTACK LIEL'S PROJECT


This project is a food delivery website 

In this project i used mongoDb, express.js, mongoose, chalk, cors, morgan, config, jsonwebtoken, joi, and bcryptjs, HTML ,CSS,bootstrap,react , typescript

The full documentation is on postman in the link: 

https://documenter.getpostman.com/view/33658895/2sAXqqcNHf

This documentation explains how to make requests including: routes, request's body and allowed users for each request.

This project is split into 2 folders: client and server

Before running:
 
 add the .env file back in the backend folder

Before running - type npm i -  in the terminal to add the node modules in both the server and the client.

To start the server on dev mode - which is the local host - type npm run dev in the terminal.
to start the client - type npm run dev in the terminal

The project is split to folders:

*controllers hold the functions.

*routes hold the routes of the requests.

*data hold the initial data that includes a few users and number of meals.

*models includes the mongoose model of a user and a meal.

*schemas holds the joi models.

*.env includes the 2 optional environments uri.

*config holds the function that changes the environments.

*the file server is the main file.

*the file seed inserts cards and users as well as allows you to delete all of them.

