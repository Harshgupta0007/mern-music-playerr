# MERN Music Player

A full-stack music player application built with the MERN stack (MongoDB, Express, React, Node.js). This application allows users to play music, manage playlists, and more.

## Features

- Play, pause, and skip tracks
- Create and manage playlists
- User authentication and authorization
- Responsive design for various devices

## Technologies Used

- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Installation

### Prerequisites

Ensure you have the following installed:
- Node.js (v14 or higher)
- npm (Node Package Manager)

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/music-player.git
   cd music-player
Install Dependencies

Navigate to the server directory and install backend dependencies:
cd server
npm install


Navigate to the client directory and install frontend dependencies:
cd ../client
npm install


Configure Environment Variables

Create a .env file in the server directory and add the following variables:
MONGODB_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret
Replace your-mongodb-connection-string with your MongoDB connection URI and your-jwt-secret with a secret key for JWT.

Run the Application

To start the backend server:
cd server
npm start


To start the frontend React application:
cd ../client
npm start
The backend server will be available at http://localhost:5000 and the React frontend will be available at http://localhost:3000.

Access the Application

Open your browser and navigate to http://localhost:3000 to use the music player.

Usage
Play Music: Click on the play button to start playing a track.
Manage Playlists: Use the playlist management options to create and edit playlists.
User Authentication: Sign up and log in to access personalized features.
