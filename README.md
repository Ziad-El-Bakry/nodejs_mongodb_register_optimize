📌 User Registration Project using Node.js and MongoDB

This project is a simple application for registering and managing users using Node.js and MongoDB.

🚀 Features

Create a new user account.

Login using email and password.

Store user data in a MongoDB database.

Well-structured and easy to scale.

🛠️ Requirements

Before running the project, make sure you have installed:

Node.js

MongoDB

📂 Project Structure
nodejs_mongodb_register_optimiz2/
│── server.js          # Main server file
│── models/User.js     # User model
│── package.json       # Project settings & dependencies
│── .env               # Environment variables (DB connection)
│── README.md          # Documentation file

⚙️ Setup & Run

Clone the project:

git clone <repo-link>
cd nodejs_mongodb_register_optimiz2


Install dependencies:

npm install


Create a .env file and add MongoDB connection details:

MONGO_URI=mongodb://localhost:27017/userDB
PORT=3000


Run the project:

npm start

📡 API Endpoints

POST /register → Register a new user.

POST /login → Login.

🧑‍💻 Contribution

Contributions are welcome! You can fork the repo, make changes, and submit a pull request.

📜 License

This project is licensed under the MIT License
.
