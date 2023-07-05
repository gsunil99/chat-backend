# Real-time Chat Backend [**Live**](https://gsunil-chat-react.netlify.app/)

This is the backend server for a real-time chat application built with Node.js and Socket.IO. The server handles WebSocket connections and enables real-time bidirectional communication between the client and server.

## Frontend code:

the frontend code is available at here (https://github.com/gsunil99/chat-frontend)

## Features

- WebSocket communication: Enables real-time messaging between clients and the server.
- Socket.IO: JavaScript library for enabling real-time bidirectional communication.
- Message broadcasting: The server broadcasts messages to all connected clients, facilitating real-time chat functionality.

## Technologies Used

- Node.js: JavaScript runtime environment for running the backend server.
- Socket.IO: JavaScript library for enabling real-time bidirectional communication.
- Express: Web framework for Node.js used for handling HTTP requests.
- Deployment: The server is deployed on Render, a cloud platform for hosting and scaling applications.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager) should be installed on your machine.

### Installation

1.  Clone the repository: `git clone https://github.com/gsunil99/chat-backend.git`
2.  Navigate to the project directory: `cd chat-backend`
3.  Install dependencies: `npm install`

### Configuration

1.  Open the `index.js` file and customize the server configuration if needed.

### Running the Server Locally

1.  Start the server: `npm start`
2.  The server will be running at `http://localhost:3000`.

### Deployment

The backend server can be deployed on Render using the following steps:

1.  Sign up for an account on [Render](https://render.com/) if you haven't already.
2.  Create a new Render service and configure it to use Node.js.
3.  Link your GitHub repository to the Render service.
4.  Configure the necessary environment variables in the Render service settings.
5.  Deploy the server using the Render dashboard or through Git-based deployments.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Socket.IO](https://socket.io/) - JavaScript library for real-time communication.
- [Express](https://expressjs.com/) - Web framework for Node.js.

Feel free to customize this README file based on your specific application and requirements.
