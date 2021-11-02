# Express JWT (micro project)

## Definition

This project build a NodeJS JWT authentication server, with ExpressJS and PassportJS

---

## How to use

### Dependencies

To install the needed dependencies use the command: `$ npm install`

### Database

The authentication data are stored in a MongoDB database
If you don't have one, you can easily create one by following [this tutorial](https://www.mongodb.com/basics/mongodb-atlas-tutorial "MongoDB Tutorial")

### Environment variables

You need to provide two environment variables :

Create a .env file (copy the .env.sample file), and provide the following variables:
- JWT_SECRET=A secret key to sign your JWT
- MONGODB_URI=The mongoDB URI to connect to your database

### Launch the server

To launch the server use the command `$ npm run start`

---

## Techs and Tools

### NodeJS

Node.js is a free, open-sourced, cross-platform JavaScript run-time environment that lets developers write command line tools and server-side scripts outside of a browser.

### ExpressJS

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

### PassportJS

Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more.

### MongoDB (and MongoDB Atlas)

MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas.

MongoDB Atlas is an integrated suite of cloud database and data services to accelerate and simplify how you build with data.

### JWT

JSON Web Tokens are an open, industry standard RFC 7519 method for representing claims securely between two parties.