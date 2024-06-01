# Blog Website Backend

Welcome to the backend repository for our blog website! This repository contains the server-side code built using Node.js to support the functionality of our blog application.

## Technologies Used

- Node.js: Used to create the backend server and handle API requests.
- Express.js: Used as the web framework to simplify routing and middleware creation.
- MongoDB: Used as the database to store blog posts, comments, and user information.
- Mongoose: Used as an Object Data Modeling (ODM) library for MongoDB to simplify interactions with the database.
- Postman: Used for API testing and development.
- React (Frontend): Although this repository focuses on the backend, it's worth mentioning that our blog website's frontend is built using React.js.

## Getting Started

1. Clone the repository:
2. Install dependencies:
cd blog-backend
npm install
3. Set up MongoDB:
- Create a MongoDB database and configure the connection string in a `.env` file.
4. Run the server:npm start
5. Use Postman to test API endpoints:
- Import the Postman collection provided in the `postman_collection.json` file.
- Test endpoints for creating, updating, deleting blog posts, managing comments, and user authentication.

## API Endpoints

- GET `/posts`: Get all blog posts.
- GET `/posts/:id`: Get a specific blog post by ID.
- POST `/posts`: Create a new blog post.
- PUT `/posts/:id`: Update an existing blog post.
- DELETE `/posts/:id`: Delete a blog post by ID.
- POST `/comments`: Add a comment to a blog post.
- DELETE `/comments/:id`: Delete a comment by ID.
- POST `/login`: User login endpoint.
- POST `/register`: User registration endpoint.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.
## Contact
For any questions or feedback, please contact us at [merugu.adithya.29@gmail.com](mailto:merugu.adithya.29@gmail.com).
