# MERN ChatApp

A real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This project demonstrates how to create a full-stack application with real-time communication using WebSockets.


## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- User authentication (login and signup)
- Real-time messaging
- Create and join chat rooms
- User profile management
- Responsive design

## Demo 
Check out the live demo of the application: [MERN ChatApp](https://igluz-chatapp.onrender.com)

## Installation

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Backend Setup

1. Clone the repository

```bash 
	git clone https://github.com/thegoofy-dev/MERN-ChatApp.git
	cd MERN-ChatApp 
```


2. Navigate to the backend directory
```bash		
	cd backend
```
3. Install dependencies
```bash
	npm install
```
4. Create a .env file in the backend directory and add the following environment variables
```bash
	PORT=5000
	MONGO_URI=your_mongodb_uri
	JWT_SECRET=your_jwt_secret
```

5. Start the backend server
```bash
	npm run dev
```
### Frontend Setup
1. Navigate to the frontend directory
```bash
	cd ../frontend
```
2. Install dependencies
```bash
	npm install
```
3. Start the frontend server
```bash
	npm run dev
```

### Usage
1. Open your browser and navigate to http://localhost:5000
2. Sign up for a new account or log in with existing credentials
3. Create or join chat rooms and start messaging in real-time
### Technologies Used
- Frontend
	- React.js
	- Redux
	- Axios
	- Socket.io-client
	- Material-UI
- Backend
	- Node.js
	- Express.js
	- MongoDB
	- Mongoose
	- JWT (JSON Web Tokens)
	- Socket.io
### Project Structure

	MERN-ChatApp/
	├── backend/
	│   ├── config/
	│   ├── controllers/
	│   ├── models/
	│   ├── routes/
	│   ├── utils/
	│   ├── .env
	│   ├── server.js
	│   └── ...
	├── frontend/
	│   ├── public/
	│   ├── src/
	│   │   ├── components/
	│   │   ├── pages/
	│   │   ├── redux/
	│   │   ├── utils/
	│   │   ├── App.js
	│   │   └── index.js
	│   └── ...
	└── README.md
	
### Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (```git checkout -b feature/AmazingFeature```)
3. Commit your Changes (```git commit -m 'Add some AmazingFeature```)
4. Push to the Branch (```git push origin feature/AmazingFeature```)
5. Open a Pull Request
### License
Distributed under the MIT License. See LICENSE for more information.

### Contact
Pankaj Tyagi - LinkedIn - sujaltyagi7788@gmail.com

Project Link: https://github.com/thegoofy-dev/MERN-ChatApp
