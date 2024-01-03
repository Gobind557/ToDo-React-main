# To-Do App

![Screenshot 2023-10-20 025047](https://github.com/s4chin-verma/ToDo-React/assets/101526717/cde8ff81-cc55-44e2-bdd0-d439a492720c)

**Summary**

This To-Do app is a full-stack application built using React.js, Vite, MDB Bootstrap on the frontend, and Node.js with Express.js on the backend. User authentication is handled using JWT tokens, and data is stored in a MongoDB database. The app provides features for managing to-do lists, user registration and authentication, task creation, editing, and deletion.

## Technology Stack

- **Frontend**: React.js, Vite, MDB Bootstrap
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT Tokens


## Getting Started

**Prerequisites:**

- [Node.js](https://nodejs.org/) installed on your system
- A package manager like [npm](https://www.npmjs.com/)
- A MongoDB database set up

**Installation:**

1. Clone the repository:

   ```bash
   git clone 

2. Open the project folder in your code editor.
   
3. Environment Variables

   Before running the frontend or backend, make sure to set up your environment variables. Create a `.env` file in the respective directories and define the following variables:
   
      - `PORT`: Set the server port, e.g., `PORT = 4000`
      - `MONGO_URL`: Specify your MongoDB connection URL, e.g., `MONGO_URL = mongodb://localhost:27017/mydatabase`
      - `JWT_SECRET`: Set your JSON Web Token secret, e.g., `JWT_SECRET = mysecretkey`

5. Open the terminal of your code editor.

6. Start the frontend development server:  

   ```bash
   cd client
   npm install
   npm run dev
This will launch the frontend application on http://localhost:5173.

5. Start the backend server:

   ```bash
   cd server
   npm install
   npx nodemon index.js
   

## Contributing

**Contributions to this project are welcome! If you'd like to contribute, please follow these steps:**

1. Fork the project.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to this repository.






