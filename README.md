Simple Chat Application

This is a simple real-time chat application built with Node.js, Express.js, Socket.IO, JWT, and EJS.
Users can log in and start chatting with each other instantly.

🚀 Features

Real-time messaging with Socket.IO

User authentication using JWT

Simple UI with EJS

REST structure with Express.js

Clean and minimal project structure

🛠 Tech Stack

Node.js

Express.js

Socket.IO

jsonwebtoken (JWT)

EJS

📂 Project Structure (example)
├── public/           # Static files (css, js, images)
├── views/            # EJS templates (login.ejs, chat.ejs)
├── routes/           # Express routes
├── app.js            # Main application file
├── package.json

⚙️ Installation

Clone the repository:

git clone https://github.com/username/chat-app.git
cd chat-app


Install dependencies:

npm install


Create a .env file and set your environment variables:

JWT_SECRET=supersecretkey
PORT=3000


Start the application:

npm start


Open in your browser:

http://localhost:3000

🔒 Authentication

A JWT is generated when a user logs in.

Access to the chat page is protected and requires a valid token.
