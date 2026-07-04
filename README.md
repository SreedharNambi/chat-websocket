# Chat Websocket

A real-time chat application built with Express and Socket.IO.

## Features

- Real-time messaging via WebSockets
- Live count of connected clients
- Typing feedback indicator
- Message notification sound

## Getting Started

### Prerequisites

- Node.js

### Install

```bash
npm install
```

### Run

```bash
npm start
```

For development with auto-restart on file changes:

```bash
npm run dev
```

The server runs on `http://localhost:3000` by default (or the port set in the `PORT` environment variable).

## Project Structure

```
.
├── app.js              # Express + Socket.IO server
└── public/             # Static client files
    ├── index.html
    ├── main.js
    ├── style.css
    └── message-tone.mp3
```
