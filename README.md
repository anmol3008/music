# Sangeetify Music Web App

[Live Demo](https://sangeetify.onrender.com/) | [GitHub Repository](https://github.com/anmol3008/music/)

***

## Project Overview

Sangeetify is a modern real-time music streaming platform built on the MERN stack. It offers synchronized playback, private messaging, and admin-controlled music management, delivering an immersive shared listening experience.

***

## Features

- **Real-time synchronized music playback** via Socket.io.
- **Admin-only controls** for creating and managing songs and albums.
- **Private user messaging** for social interaction.
- **Personalized user libraries** and playlists.
- **Secure authentication** powered by Clerk.
- **Responsive UI** with Tailwind CSS.
- **Deployed on Render** with automated CI/CD.

***

## Technology Stack

- **Frontend:** React.js, TypeScript, Tailwind CSS, Clerk Authentication
- **Backend:** Node.js, Express.js, MongoDB, Socket.io
- **Deployment:** Render platform with GitHub-based CI/CD
- **Tools:** Git, Vite, Cloudinary for media management

***

## Project Architecture

- React frontend communicates with backend REST and WebSocket APIs.
- Express backend serves APIs, manages authentication, and real-time events.
- MongoDB stores users, music metadata, and messages.
- Socket.io enables synchronized audio and messaging.
- Clerk handles user authentication and session management.
- Cloudinary manages image and media uploads.

***


## Installation and Setup
1. **Clone the repository**
```
git clone https://github.com/anmol3008/music.git   
cd music
```

2. **Setup and start backend**
```
cd backend  
npm install
```
Create .env file with your secure backend variables (see below)  
```
npm run dev
```

3. **Setup and start frontend**
```
cd ../frontend
npm install
```
Create .env file with your secure frontend variables (see below) 
```
npm run dev
```
4. **Access the app**

Open browser at `http://localhost:3000`

***
## Environment Variables

### Frontend (`.env` file in frontend folder)
```
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
```
***

### Backend (`.env` file in backend folder)

```env
PORT=5000  
MONGODB_URI=your_mongodb_connection_string_here

ADMIN_EMAIL=your_admin_email_here

CLOUDINARY_API_KEY=your_cloudinary_api_key_here
CLOUDINARY_API_SECRET=your_cloudinary_api_secret_here
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name_here

NODE_ENV=development

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
CLERK_SECRET_KEY=your_clerk_secret_key_here
```

*Replace all placeholders with the actual secure values in your local `.env` files.*

***

## Usage

- Sign up or sign in via Clerk (email/social login).
- Browse and listen to music tracks synchronized in real time.
- Admins can create albums and songs.
- Chat privately with online users.
- Manage personalized libraries and playlists.

***

## Links

- GitHub Repository: https://github.com/anmol3008/music/
- Live Deployment: https://sangeetify.onrender.com/

***

## Contact

**Anmol Kumar**  
Email: anmolkumar30082005@gmail.com  
GitHub: [anmol3008](https://github.com/anmol3008)  
LinkedIn: [Anmol Kumar](https://www.linkedin.com/in/anmol3008)


***

