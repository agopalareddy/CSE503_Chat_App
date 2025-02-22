# Socket.IO Multi-Room Chat Application

This project is a multi-room chat application built using Node.js and Socket.IO. It features password-protected rooms, private messaging, and user moderation capabilities.

## Features

- Multi-room chat support with a default "Lobby"
- Password protection for private rooms
- Room creator privileges (kick/ban users)
- Private messaging between users
- Persistent nickname storage using localStorage
- Message reply functionality
- User room history tracking
- Style customization via CSS

## Project Structure

- **chat-server.js**: Manages room creation, user sessions, message handling, and moderation features.
- **client.html**: Provides the user interface with room management, messaging, and moderation controls.
- **style.css**: Contains the application's styling.
- **package.json**: Lists project dependencies and scripts.

## Getting Started

1. **Clone the repository** or download the files to your local machine.

2. **Navigate to the project directory**:
   ```
   cd socketio-chat-app
   ```

3. **Install the dependencies**:
   ```
   npm install
   ```

4. **Start the server**:
   ```
   npm start
   ```
   5. **Open your browser** and navigate to [http://localhost:3456/client.html](http://localhost:3456/client.html). You can open this URL in multiple tabs or windows to simulate multiple users.

## Usage

- Set your nickname to join the chat (automatically remembered)
- You're already in the Lobby. You can create your own room with optional password protection
- Send messages in rooms or privately to other users
- Reply to specific messages
- Room creators can:
  - Kick or ban users
  - Manage room access
  - Delete the room