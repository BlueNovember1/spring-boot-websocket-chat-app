# Spring boot chat application

Description
This project consists of separate websites for the backend and frontend. It provides the following functionality:

Enables the exchange of messages between two selected users.
Allows viewing the global list of users.
Requirements
Separate websites for backend and frontend:

The backend and frontend are structured as separate services to maintain a clean separation of concerns.
Each service can be hosted independently.
Message exchange between two selected users:

Users can select another user from the global list and send direct messages in real time.
This feature is implemented using WebSockets or REST API for real-time communication.
Global list of users:

The application displays a list of all registered users.
Users can select anyone from the list to start a conversation.
Project Structure
The project follows a modular structure with two main components:

frontend/: This folder contains the frontend website built using modern web technologies (e.g., React, Angular, Vue).
backend/: This folder contains the backend API, which is responsible for handling authentication, message exchange, and user management (e.g., Node.js, Express, Django).
