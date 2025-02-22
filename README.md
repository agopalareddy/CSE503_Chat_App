# Socket.IO Multi-Room Chat Application

## Overview

This project implements a real-time chat application using Socket.IO and Node.js, featuring multi-room support, private messaging, and user moderation. It was developed as part of Washington University in St. Louis's CSE 503S: Rapid Prototyping and Creative Programming course.

## Features

- Multi-room chat with password protection
- Private messaging between users
- Room moderation (kick/ban users)
- Message replies and deletion
- Persistent chat history
- User authentication
- Mobile-responsive design

## Repository Structure

### Core Files
- [socketio-chat-app/chat-server.js](socketio-chat-app/chat-server.js) - Server implementation
- [socketio-chat-app/client.html](socketio-chat-app/client.html) - Web client interface
- [socketio-chat-app/client.js](socketio-chat-app/client.js) - Client-side logic
- [socketio-chat-app/style.css](socketio-chat-app/style.css) - Application styling

### Configuration
- [socketio-chat-app/package.json](socketio-chat-app/package.json) - Project dependencies

## Getting Started

1. Install dependencies:
```sh
cd socketio-chat-app
npm install
```

2. Start the server:
```sh
npm start
```

3. Open `http://localhost:3456` in your browser

## Technologies

- Node.js
- Socket.IO
- HTML5/CSS3
- JavaScript

## Acknowledgments

Developed for CSE 503S at Washington University in St. Louis.