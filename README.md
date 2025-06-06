A full-stack blogging platform that allows users to register, login, create, edit, and delete blog posts. Built with React for the frontend, Node.js and Express for the backend, and MongoDB as the database.

Features: 

1.User authentication (signup, login) with JWT

2.Create, read, update, and delete (CRUD) blog posts

3.Responsive UI with Ant Design components

4.Secure password hashing with bcrypt

5.RESTful API backend with Express.js

6.MongoDB database for persistent storage

Tech Stack:

1.Frontend: React, Ant Design, Axios, React Router

2.Backend: Node.js, Express.js, Mongoose, JWT, bcrypt

3.Database: MongoDB (Atlas or local)

4.Authentication: JWT tokens

5.Deployment: Netlify

Getting Started Prerequisites

1.Node.js 

2.npm 

3.MongoDB Atlas

Installation:

1.Clone the repository: 

git clone https://github.com/pavanchinna96535/blog-platform.git
cd blog-platform

2.Install backend dependencies:

cd server
npm install

3.Create a .env file inside the server directory with the following variables:

PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

4.Start the backend server:

npm run dev 

5.Install frontend dependencies:

cd ../client
npm install

6.Start the frontend:

npm start 

7. Open http://localhost:3000 in your browser.

Usage:

1.Register a new account

2.Login to access blog creation 

3.Create, edit, and delete your own blog posts

4.View all blogs publicly

Folder structure:

blog-platform/
│
├── client/           
├── server/          
├── README.md
└── .gitignore

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.

Contact
Your Name — pavanchinnadoraij1@gmail.com
Project Link: https://github.com/pavanchinna96535/blog-platform

