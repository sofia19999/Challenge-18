
## Social Network API


## Description
This project is a Social Network API built using Express.js, MongoDB, and Mongoose. It allows users to create a social network where they can share their thoughts, react to friends' thoughts, and manage a friend list. This API is designed to handle large amounts of unstructured data using a NoSQL database.

## Table of Contents
* Installation
* Usage
* API Endpoints
* Walkthrough Video
* Technologies Used
* License
* Installation
* Clone the repository to your local machine.

## Installation instructions:
1. Copy code
git clone https://github.com/sofia19999/Challenge-18.git


2. Navigate to the project directory.

 cd social-network-api

3. Install the necessary dependencies.

npm install

Ensure MongoDB is running on your local machine.

4. Usage

Start the server.

node server.js 

API Endpoints
User Routes
GET /api/users - Retrieves all users.
GET /api/users/:id - Retrieves a user by their ID.
POST /api/users - Creates a new user.
PUT /api/users/:id - Updates a user by their ID.
DELETE /api/users/:id - Deletes a user by their ID.
Friend Routes
POST /api/users/:userId/friends/:friendId - Adds a friend to the user's friend list.
DELETE /api/users/:userId/friends/:friendId - Removes a friend from the user's friend list.
Thought Routes
GET /api/thoughts - Retrieves all thoughts.
GET /api/thoughts/:id - Retrieves a thought by its ID.
POST /api/thoughts - Creates a new thought and associates it with a user.
PUT /api/thoughts/:id - Updates a thought by its ID.
DELETE /api/thoughts/:id - Deletes a thought by its ID.
Reaction Routes
POST /api/thoughts/:thoughtId/reactions - Adds a reaction to a thought.
DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Removes a reaction from a thought.



## Walkthrough Video
A walkthrough video demonstrating the functionality of this API can be found here.

https://drive.google.com/file/d/1wYvioV4N54PDGp_iP7yFv4wh7XDEGbXO/view


## Technologies Used
- Node.js - JavaScript runtime environment.
- Express.js - Web framework for Node.js.
- MongoDB - NoSQL database.
- Mongoose - MongoDB object modeling tool for Node.js.
- ChatGPT
- Stack Overflow
- Day.js - Lightweight date library for formatting timestamps.


## License
This project is licensed under the MIT License.









