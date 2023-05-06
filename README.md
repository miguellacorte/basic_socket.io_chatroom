# Basic Socket.io Chatroom (React)

[Basic Socket.io Chatroom](https://github.com/miguellacorte/basic_socket.io_chatroom_react) is a repository containing a simple chatroom application built with React and Socket.io. The purpose of this project is to provide a basic implementation of a real-time chatroom using WebSocket communication.

## Features
- Real-time communication: Users can join the chatroom and exchange messages in real-time.
- User identification: Each user is assigned a unique username upon joining the chatroom.
- Message broadcasting: Messages sent by a user are broadcasted to all connected users in the chatroom.
- Display of active users: The chatroom displays a list of active users currently connected.

## Technical Framework
- Frontend: The frontend of the application is built using React, a popular JavaScript library for building user interfaces. React components are used to create the chatroom interface and handle user interactions.
- Socket.io: Socket.io is a JavaScript library that enables real-time, bidirectional communication between web clients and servers. It is used in this project to establish WebSocket connections and facilitate real-time messaging in the chatroom.
- Express.js: Express.js is a web application framework for Node.js. It is utilized in the backend to serve the React frontend and handle WebSocket connections with Socket.io.
- Socket.io Client: The Socket.io client library is used on the frontend to establish a connection with the server and enable real-time communication.

## Usage
To run the chatroom application locally, follow these steps:
1. Clone the repository: `git clone https://github.com/miguellacorte/basic_socket.io_chatroom_react.git`
2. Navigate to the project directory: `cd basic_socket.io_chatroom_react`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Access the chatroom in your browser at `http://localhost:3000`

Feel free to modify the code and customize the chatroom according to your requirements.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/miguellacorte/basic_socket.io_chatroom_react/blob/main/LICENSE) file for more details.
