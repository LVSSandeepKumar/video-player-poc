# Video Player POC

## Overview
This is a simple video player proof of concept built using the MERN stack (MongoDB, Express, React, Node.js). It demonstrates the basic functionality of a video player, including uploading and playing videos.

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [File Structure](#file-structure)
5. [Key Coding Takeaways](#key-coding-takeaways)
6. [Contributing](#contributing)
7. [Acknowledgements](#acknowledgements)

## Features
- Upload and play videos
- Basic video player controls (play, pause, seek)

## Installation
### Prerequisites
- Node.js and npm installed
- MongoDB installed and running

### Steps
1. Clone the repository:
    ```sh
    git clone https://github.com/LVSSandeepKumar/video-player-poc.git
    ```
2. Navigate to the project directory:
    ```sh
    cd video-player-poc
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```
4. Set up the environment variables (create a `.env` file in the root directory with the necessary variables):
    ```env
    MONGO_URI=<your_mongodb_connection_string>
    ```
5. Start the server:
    ```sh
    npm run start
    ```
6. Navigate to the `frontend` directory and install the dependencies:
    ```sh
    cd frontend
    npm install
    ```
7. Start the frontend application:
    ```sh
    npm run dev
    ```
8. Open [http://localhost:3000](http://localhost:3000) in your web browser to view the application.

## Usage
- Upload videos via the upload interface
- Use the player controls to play, pause, and seek through the videos

## File Structure
The file structure includes:
- **frontend/**: Contains the React frontend application.
  - **public/**: Public assets and HTML files.
  - **src/**: Source code for the frontend application.
    - **components/**: Reusable React components.
    - **pages/**: Main pages of the application.
    - **styles/**: CSS files for styling the application.
- **index.js**: Entry point for the Node.js server.
- **package.json**: Project metadata and dependencies.
- **README.md**: Project documentation.

## Key Coding Takeaways
- **MERN Stack**: Utilization of MongoDB, Express, React, and Node.js for full-stack development.
- **File Handling**: Implementation of video file upload and storage.
- **Video Playback**: Integration of HTML5 video player for seamless video playback.
- **Component-Based Architecture**: Modular design with reusable React components.
- **Responsive Design**: Ensuring the application looks great on all devices.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request.

## Acknowledgements
- Built using the MERN stack.
