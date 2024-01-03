# To-Do App



![register](https://github.com/Gobind557/ToDo-React-main/assets/72307219/9a022298-cf68-4f05-9474-2a9cb74dffcf)
![login](https://github.com/Gobind557/ToDo-React-main/assets/72307219/7c811e49-8a54-4cab-ad94-1696be22e730)
![UI](https://github.com/Gobind557/ToDo-React-main/assets/72307219/067a76de-fccd-44b1-982c-e77b35b2a80f)
![Task_check](https://github.com/Gobind557/ToDo-React-main/assets/72307219/2d78f1a1-36e7-4165-bcbe-5d9de471299b)



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
   



