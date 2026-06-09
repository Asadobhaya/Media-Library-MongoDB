# 🎵 MediaLib - Scalable Music Streaming & Library System

## Overview

MediaLib is a cloud-connected music streaming and library management system developed using MongoDB Atlas and Node.js.

The system allows users to:

- Stream songs using YouTube integration
- Create and manage playlists
- Rate and comment on songs
- Search and filter media
- View analytics dashboards
- Manage content through an admin panel

---

## Features

### User Features

- User Registration
- User Login
- JWT Authentication
- Search Songs
- Genre Filtering
- Create Playlists
- Rate Songs
- Comment on Songs
- View Song Statistics

### Admin Features

- Add Songs
- Edit Songs
- Delete Songs
- Manage Music Library
- Analytics Dashboard

---

## Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### Backend

- Node.js
- Express.js

### Database

- MongoDB Atlas
- Mongoose

### Security

- JWT Authentication
- bcrypt Password Hashing

---

## Database Collections

1. Users
2. Songs
3. Playlists
4. Ratings
5. Comments
6. PlayHistories

---

## Advanced Database Concepts Implemented

- CRUD Operations
- Aggregation Pipelines
- MongoDB Views
- Indexing
- Query Optimization
- ACID Transactions
- Concurrency Control
- Validation Rules
- Cloud Database Integration

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/MediaLib.git
cd MediaLib
```

### Install Dependencies

```bash
npm install
```

### Create Environment File

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Initialize Database

```bash
node setup.js
```

### Start Application

```bash
node server.js
```

---

## Project Structure

```
MediaLib/
│
├── config/
│   └── db.js
│
├── middleware/
│   └── auth.js
│
├── models/
│   ├── User.js
│   ├── Song.js
│   ├── Playlist.js
│   ├── Rating.js
│   ├── Comment.js
│   └── PlayHistory.js
│
├── routes/
│   ├── auth.js
│   ├── songs.js
│   ├── playlists.js
│   ├── ratings.js
│   ├── comments.js
│   └── stats.js
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── app.js
│
├── setup.js
├── server.js
├── package.json
└── README.md
```

---

## Project Owner


|--------|--------|
| Muhammad Rizwan |  



---

## Course Project

Advanced Database Systems Project

Institute of Space Technology (IST)

---

## License

This project is developed for educational purposes.