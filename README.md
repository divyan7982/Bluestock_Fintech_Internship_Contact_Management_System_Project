# Contact Management System

![image](https://github.com/user-attachments/assets/cbe7b178-7dd1-4d5c-a8e4-d3484642d957)

## Project Overview

The **Contact Management System** is a full-stack application designed to manage contacts efficiently. Built using the MERN (MongoDB, Express, React, Node.js) stack, this application provides features such as adding, editing, and deleting contacts, along with a responsive user interface.

## Features

- **User Authentication**: Secure login and registration with JWT-based authentication.
- **Contact Management**: Add, edit, delete, and view contacts.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: React, React Router DOM, Axios, React Transition Group
- **Backend**: Node.js, Express, Mongoose, JWT, bcryptjs
- **Database**: MongoDB
- **Dev Tools**: Nodemon, Concurrently

## Installation

### Prerequisites

- Node.js and npm installed on your local machine.
- MongoDB installed locally or a MongoDB Atlas account.

### Setup Instructions

1. **Clone the repository**:
   ```bash
      git clone https://github.com/yourusername/contact-management-system.git
      cd contact-management-system

2. Install server dependencies:
   ```bash
      npm install

3. Install client dependencies:
   ```bash
      npm run client install

4. Set up environment variables:
   Create a .env file in the root directory and add your configuration values:
   ```bash
      MONGO_URI=your_mongodb_uri
      JWT_SECRET=your_jwt_secret

5. Run the application:
   ```bash
      npm run dev
   

## Usage
- **Access the app**: Open your browser and go to http://localhost:3000 to start using the application.
- **Create an account**: Register a new user account to begin managing your contacts.
- **Add transactions**: Add, edit, delete, and view contacts through the user-friendly interface.

## Scripts
- **npm start**: Start the server.
- **npm run server**: Start the server with Nodemon.
- **npm run client**: Start the React development server.
- **npm run clientinstall**: Install dependencies in the client directory.
- **npm run dev**: Run both the server and the React development server concurrently.
- **npm run build**: Build the React app for production.



  
