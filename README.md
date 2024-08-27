# Real-time Collaborative Whiteboard 

## Overview
This web application allows users to upload images and receive real-time predictions from a pre-trained machine learning model. The app also features a real-time collaborative whiteboard, where users can draw, see others' actions in real-time, and save their work. The application ensures secure access through Keycloak authentication and is designed to work seamlessly across devices.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Demo]
- [Screenshots]
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features
- **Image Upload & Classification**: Users can upload images and receive real-time predictions from a pre-trained machine learning model.
- **Collaborative Whiteboard**:
  - **Drawing Tools**: Multiple brush sizes and colors.
  - **Undo/Redo**: Ability to undo and redo actions.
  - **Real-time Collaboration**: See other users' cursors and actions in real-time.
  - **Session Management**: Create or join a whiteboard session.
  - **Save Whiteboard**: Export the whiteboard content as an image or PDF.
- **Authentication**: Secure user authentication with Keycloak via Docker.
- **Responsive Design**: Works on both desktop and mobile devices.

### Bonus Features
- **Live Chat**: Users can chat while drawing on the whiteboard.
- **Invitation System**: Invite others to join the session via email.
- **Export as Video**: Export the whiteboard content as a video with playback of drawing actions.

## Getting Started
### Prerequisites
- **Node.js** (v14.x or higher)
- **npm** or **yarn**
- **Docker**
- **Git**

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Anand5d7/Real-time-Collaborative-Whiteboard.git
   cd Real-time-Collaborative-Whiteboard
   ```
2. **Install dependencies**:
   ```bash
     npm install
   ```
3. **Set up Keycloak**:
   - Ensure Docker is installed and running.
   - Pull and run the Keycloak Docker image
4. **Start the application**:
   ```bash
     npm run dev
   ```
5. **Access the application**:
   - Navigate to `http://localhost:3000`.
### Usage
1. **Login**:
   - Users must log in via Keycloak to access the whiteboard.
2. **Create or Join a Session**:
   - Start a new whiteboard session or join an existing one.
3. **Upload and Classify Images**:
   - Upload an image to receive real-time predictions.
4. **Draw on the Whiteboard**:
   - Use the drawing tools to collaborate in real-time with others.
5. **Save Your Work**:
   - Export the whiteboard content as an image, PDF, or video.

### Technologies Used
  - **Frontend**: React, TypeScript, Bootstrap 5
  - **Backend**: Node.js, Express.js
  - **Authentication**: Docker
  - **Real-time Features**: WebSocket, Socket.IO
  - **Drawing Libraries**: Collabio
  - **Others**: ESLint, Prettier
### License
- This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments
- Keycloak for authentication.
- Fabric.js / Konva.js for the drawing tools.
- The community for feedback and contributions.
## Demo

LIVE DEMO: https://collabio-kriziu.herokuapp.com

## Screenshots

#### Home page
![Collabio _ Online Whiteboard - Google Chrome 27-08-2024 17_09_44](https://github.com/user-attachments/assets/794c8896-3a43-4074-81a1-a879a9d1e695)

#### Board page
![Collabio _ Online Whiteboard - Google Chrome 27-08-2024 17_17_27](https://github.com/user-attachments/assets/21b01168-bbb4-4ca8-8d0e-a856eb325e98)

