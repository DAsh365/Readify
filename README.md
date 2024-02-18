# Readify

## Description

This project refactors an existing book search engine, transitioning from a RESTful API to a GraphQL API using Apollo Server. Built with the MERN stack (MongoDB, Express.js, React, Node.js), it allows users to search for books via the Google Books API, save their favorites, and manage their saved list. The application includes updated authentication middleware compatible with GraphQL and utilizes an Apollo Provider for seamless communication between the React front end and Apollo Server. It is deployed on Render, integrated with MongoDB Atlas for database management.

## Features

- Search for books using Google Books API
- User authentication (login/signup) with JWT
- Save favorite books to a personal list
- View and manage saved books
- GraphQL API with Apollo Server for efficient data retrieval and manipulation
- Deployed to Render with MongoDB Atlas for database services

## Technologies Used

- MongoDB/Mongoose for database management
- Express.js and Node.js for server-side
- React for the front end
- GraphQL with Apollo Server for the API
- JWT for authentication
- Deployed on Render with MongoDB Atlas

## Deployment

This application is deployed on Render. Access it [here](https://readify-cfer.onrender.com).

## Installation and Setup

1. Clone the repository.
2. Install dependencies with `npm install`.
3. Set up your MongoDB Atlas database and connect it to the application.
4. Start the server with `npm start`.
5. Access the application locally or via the deployment link provided.

## Usage

- Visit the deployed application link.
- Search for books using the search bar.
- Log in or sign up to save books to your account and view your saved book list.
- Manage your saved books with options to save new books or remove existing ones from your list.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributions

Contributions are welcome. Please open an issue or submit a pull request with any improvements.

## Questions

For questions and support, please open an issue in the repository.