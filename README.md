# Real-time Collaborative Whiteboard
## Overview
This web application allows users to upload images and receive real-time predictions from a pre-trained machine learning model. The app also features a real-time collaborative whiteboard, where users can draw, see others' actions in real-time, and save their work. The application ensures secure access through Keycloak authentication and is designed to work seamlessly across devices.

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

Here's a README file tailored to your project requirements:

markdown
కాపీ కోడ్
# Real-time Collaborative Whiteboard with Image Classification

## Overview
This web application allows users to upload images and receive real-time predictions from a pre-trained machine learning model. The app also features a real-time collaborative whiteboard, where users can draw, see others' actions in real-time, and save their work. The application ensures secure access through Keycloak authentication and is designed to work seamlessly across devices.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
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
4. **Access the application**:
   - Navigate to `http://localhost:3000`.
## Demo

LIVE DEMO: https://collabio-kriziu.herokuapp.com

## Screenshots

#### Home page
![home page](https://i.imgur.com/00CZlrR.png)

#### Board page
![Board page](https://i.imgur.com/0v4Y8XP.png)
