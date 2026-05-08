# Real-Talk Chat Application

A basic real-time chat server built with Node.js and Socket.io.

## Overview

This sample demonstrates how to implement a basic chat application in Node.js using the Socket.io library for real-time bidirectional communication between clients and server.

## Based On

- [Socket.io Documentation](https://socket.io)
- [Socket.io Getting Started Guide](https://socket.io/docs/)
- [Socket.io Chat Example](https://socket.io/get-started/chat/)

## Prerequisites

- Node.js and npm installed

## Getting Started

### 1. Install Dependencies

```bash
npm install
```

This will install Socket.io and generate/update `package-lock.json`.

### 2. Run the Server

```bash
node server.js
```

The server will start and listen on port 3000.

### 3. Access the Chat Application

Open multiple browser instances and navigate to:

```
http://localhost:3000/chatClient.html
```

Then start chatting with other connected users!

## Project Structure

- `server.js` - Main server file
- `package.json` - Project dependencies
- `html/chatClient.html` - Client UI
- `html/chatClient.js` - Client-side logic
- `.gitignore` - Git configuration (includes `.DS_Store` for macOS)

## Requirements

- Socket.io npm module
- Node.js runtime environment

## Development

To set up a fresh project:

1. Run `npm init` to create package.json
2. Run `npm install socket.io --save` to add Socket.io
3. Execute `node server.js` to start the server
