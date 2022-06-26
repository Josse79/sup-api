# Project SUP API

This sup-api repo is the backend to our final Technigo frontend project called: sup-project. This backend is made in with express service, MongoDB and Mongoose. 

## The solutions and problems

We started to create a User schema with validation in Mongoose for our login form. Adding the endpoints and testing them in Postman and verifying the data in MongoDB compass.

The Post schema with belonging endpoints were created to use for our posts pages. This was also tested in Postman and verifying in MongoDB compass as well as MongoDB Atlas Database.

As we wanted our posts to display the users email and username automatically in frontend we came to an obstacle of how to deal with this part in backend. Trying to figure out how to combine our user and post schema by googeling, searching/posting in Stack Overlow and looking into other code projects we finally made it work with help from our code coach. The solution was to create a third Creator schema, to combine with our Post and User schemas.

## View it live

https://sup-api-js.herokuapp.com/
