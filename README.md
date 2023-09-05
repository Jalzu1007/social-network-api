# social-network-api

## Description

This project involves building an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. The technology stack includes Express.js for routing, a MongoDB database, and the Mongoose ODM. The goal is to create a flexible and efficient backend API for a social networking platform.

The motivation behind this project is to gain a deeper understanding of building APIs for social networking platforms. By working with MongoDB and Mongoose, the project aims to explore how to handle unstructured data efficiently, and how to create relationships between different data entities.

The project solves the problem of creating a backend system that can handle large amounts of unstructured data efficiently. It focuses on providing the necessary API routes for users to interact with the platform, share thoughts, react to thoughts, and manage their friend list.

Through this project, I've learned how to design and implement API routes using Express.js, interact with a MongoDB database using Mongoose, manage relationships between different data models, and create a user-friendly API for a social networking platform.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To set up the project and its development environment, follow these steps:

1. Make sure you have MongoDB installed on your machine. You can follow the [MongoDB installation guide](https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb) for installation instructions.
2. Clone the repository to your local machine.
3. Navigate to the project directory using the terminal.
4. Run `npm install` to install the required dependencies.
5. Run `npm start` or `node server.js` to start the server.
6. Open your web browser or Insomnia and navigate to the provided local URL and endpoints.

## Usage

This project provides API routes to manage users, thoughts, friends, and reactions for a social network website. You can test these routes using tools like Insomnia.

API Routes

* users:
    - GET /api/users: Get all users.
    - POST /api/users: Create a new user.
    - GET /api/users:id: Get user by id.
    - PUT /api/users/:id: Update a user by ID.
    - DELETE /api/user/:id: Delete a user by ID.

* friends:
    - POST /api/users/:userId/friends/:friendId: Add a new friend.
    - DELETE /api/users/:userId/friends/:friendId: Delete a friend.

* thoughts:
    - GET /api/thoughts: Get all thoughts.
    - POST /api/thoughts: Create a new thought.
    - PUT /api/thoughts/:id: Update a thought by ID.
    - DELETE /api/thoughts/:id: Delete a thought by ID.

* reactions:
    - POST /api/thoughts/:thoughtId/reactions: Add a reaction.
    - DELETE /api/thoughts/:thoughtId/reactions: Delete a reaction.

GitHub Repository:

https://github.com/Jalzu1007/social-network-api.git

Walkthrough Video:

[![social-network-api](https://img.youtube.com/vi/GUTeYN9eM34/0.jpg)](https://youtu.be/GUTeYN9eM34)


## Credits

I used the following third-party assets in this application:

- https://youtu.be/RGfFpQF0NpE
- https://youtu.be/YBOiX8DwinE
- https://youtu.be/-PdjUx9JZ2E
- https://youtu.be/jZ-dzj6ut54
- https://youtu.be/AWlLhRQJvtw

## License

N/A