# technologies-demo
This is a simple NodeJs app based on Express and Mongoose

## Getting started

To get the Node server running locally:

- Clone this repo
- `npm install` to install all required dependencies
- create a free acount on mongo DB <https://www.mongodb.com/download-center>
- create locally the `.env`  file and set the `PORT` and  `MONGO_URI`
- `npm run dev` to start the local server

## Application Structure

- `index.js` - The entry point to our application. This file defines our express server and connects it to MongoDB using mongoose. It also requires the routes and models we'll be using in the application.
- `config/` - This folder contains configuration/environment variables.
- `server/` - This folder contains the routes and mdw's definitions for our API.
- `models/` - This folder contains the schema definitions for our Mongoose models.
