# MERN Web Blog App

This is a full-stack web application for creating and managing a blog using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to register, login, create, edit, and delete blog posts.

## Features

- User Authentication: Users can register, login, and logout securely.
- CRUD Operations: Users can create, read, update, and delete blog posts.
- Responsive Design: The application is designed to be mobile-friendly and accessible on various devices.
- Markdown Support: Blog posts can be written using Markdown syntax for formatting.
- Image Upload: Users can upload images to include in their blog posts.

## Technologies Used

- MongoDB: NoSQL database for storing blog post data.
- Express.js: Web application framework for building APIs and handling server-side logic.
- React.js: JavaScript library for building user interfaces.
- Node.js: JavaScript runtime environment for running server-side code.
- Mongoose: MongoDB object modeling for Node.js.
- JWT (JSON Web Tokens): For user authentication and authorization.
- Axios: Promise-based HTTP client for making requests to the server.
- React Router: Declarative routing for navigating between components in React.

## Installation

1. Clone the repository:

##bash
`git clone https://github.com/yourusername/mern-blog-app.git`



2. Navigate to the project directory:


`cd mern-blog-app`

Install dependencies for the server:

`npm install`

Navigate to the client directory:

`cd client`

Install dependencies for the client:

`npm install`
Return to the root directory:

`cd ..`

Create a .env file in the root directory and add the following environment variables:

`touch .env`

Open the .env file using a text editor, and add the following environment variables:
```makefile```

`MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret`
Replace your_mongodb_uri with your MongoDB connection URI and your_jwt_secret with a random string for JWT token encryption.
Start the server:

`npm run server`
In a separate terminal, start the client:

`npm run client`

Open your web browser and navigate to http://localhost:3000 to access the application.
