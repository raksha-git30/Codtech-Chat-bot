Company Name : CodeTech IT Solution

Name : Raksha Dattu Shrimanwar

Intern Id : CT04DG2657

Domain : Front-End-Development

Duration : 4 Weeks

Mentor : Neela Santosh

🗨️ Real-Time Chat Application – Project Description
This project is a real-time chat application built using modern web technologies including React.js for the front end, Node.js with Express for the backend server, and Socket.IO for enabling real-time, bi-directional communication between users. The primary goal of this project is to demonstrate a fully functional, responsive, and interactive chat interface that updates messages in real time without the need for page refreshes.

🔧 Technologies Used
Frontend: React.js, HTML, CSS, JavaScript

Backend: Node.js, Express.js

WebSockets: Socket.IO

Styling: Custom CSS

Development Environment: Visual Studio Code

Version Control: Git & GitHub

💡 Features
Real-Time Messaging
The application enables users to send and receive messages in real-time using WebSockets. As soon as a message is sent, it is instantly broadcasted to all connected users.

Simple and Clean UI
The front end is built with React.js and CSS, offering a clean, responsive interface. Users can see the message history and input new messages with ease.

Message History
The chat displays a history of messages, helping users follow the conversation contextually.

Server-Client Architecture
The application has a clear separation between the client (React frontend) and the server (Node.js backend), communicating via Socket.IO events.

⚙️ How It Works
Client Side (React App)
The frontend is hosted separately and connects to the backend via a WebSocket connection using Socket.IO. When a user types a message and hits send, the message is emitted to the server.

Server Side (Node.js)
The server listens for incoming messages and emits them to all connected clients. This ensures all users in the chat receive new messages instantly.

WebSocket Communication
Socket.IO provides real-time updates through persistent connections between the client and server. The app uses events like send_message and receive_message to handle the chat flow.

🚀 Deployment and Usage
This app can be run locally or deployed on cloud platforms like Render, Vercel, or Heroku. Users can access the chat from any modern browser. The server must be running to allow socket communication.

To run it locally:

Install dependencies (npm install)

Run the backend server (node index.js)

Start the frontend (npm start in the React folder)

🧠 Learning Outcomes
This project provided hands-on experience in:

Implementing real-time systems using WebSockets

Integrating React with backend APIs and sockets

Structuring a full-stack JavaScript project

Deploying and testing real-time applications

#output 

<img width="1915" height="1002" alt="Image" src="https://github.com/user-attachments/assets/5f474a4a-edf1-4fbd-a090-08aa927a79fe" />
