# Task_mangement_api

##Task Management API Assignment

##Overview
In this assignment, you'll build a RESTful API for a task management application using Node.js, Express, MongoDB, and dotenv.

##Objectives
Understand RESTful services.
Learn Express.js and MongoDB.
Manage environment variables with dotenv.
Implement CRUD operations.
Prerequisites
Node.js and npm: Download and install from Node.js official website.
Postman or Insomnia: API testing tools.
Postman: Download and Install
Insomnia: Download and Install

##Requirements
#1. Setup and Configuration
Initialize a new Node.js Project

In your project directory, run:
  npm init -y
This will create a package.json file.
  Install Required Packages

Install the necessary packages using:
  npm install express mongoose dotenv nodemon
  express: Framework for handling HTTP requests.
  mongoose: ORM for MongoDB.
  dotenv: Manages environment variables.
  nodemon: Automatically restarts the server on code changes.
  Configure .env File

##Create a .env file in the root directory and add the following:
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/taskdb
PORT=3000
Replace <username> and <password> with your MongoDB Atlas credentials.
PORT is the port number where the server will run.
#2. Setting Up MongoDB
Create a MongoDB Atlas Account
Go to MongoDB Atlas and sign up.
