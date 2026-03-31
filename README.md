# Google Docs Clone

A real-time collaborative document editor inspired by Google Docs. This project allows users to create a document, edit it with a rich text editor, and sync changes instantly using Socket.IO. The frontend is built with React, while the backend uses Node.js, Socket.IO, and MongoDB. :contentReference[oaicite:0]{index=0}

## Features

- Real-time collaborative editing
- Rich text editor using Quill
- Unique document creation using UUID
- Automatic document saving
- Document loading from MongoDB
- Simple client-server architecture

These features are reflected in the React client’s use of Quill, React Router, UUID, and Socket.IO, along with the server’s Socket.IO-based document loading and save/update flow backed by MongoDB. :contentReference[oaicite:1]{index=1}

## Tech Stack

### Frontend
- React
- React Router DOM
- Quill
- Material UI
- Socket.IO Client

### Backend
- Node.js
- Socket.IO
- MongoDB
- Mongoose
- dotenv

The dependencies listed in the repo match this stack. :contentReference[oaicite:2]{index=2}

## Project Structure

```bash
Google-Docs-Clone/
│── client/
│   ├── public/
│   ├── src/
│   │   ├── component/
│   │   │   └── Editor.jsx
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
│   ├── package.json
│   └── README.md
│
│── server/
│   ├── controller/
│   │   └── document-controller.js
│   ├── database/
│   │   └── db.js
│   ├── schema/
│   │   └── documentSchema.js
│   ├── index.js
│   └── package.json
│
└── README.md
