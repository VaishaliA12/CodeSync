# CodeSync

**CodeSync** is designed to revolutionize the way developers collaborate. It is a real-time collaborative code editor that brings teams together on a single platform, enabling seamless coding sessions. Built on the powerful trio of **Node.js**, **React.js**, and **Socket.io**, CodeSync ensures instant, smooth, and conflict-free synchronization of code changes.

## 🚀 Features

- Multiple users can join a room and edit code collaboratively.  
- Changes are reflected in real time for all participants. 
- Copy button to easily share the room ID.  
- Leave button to exit the session smoothly.  
- Syntax highlighting support for multiple programming languages.  
- Users can leave and rejoin a room to continue editing.  
- User join/leave events are reflected instantly in the editor.  

## 🛠 Tech Stack

- React.js  
- Node.js  
- Express.js  
- Socket.io  

## ✅ Prerequisites

Make sure you have the following installed:

- **Node.js** (v20.11.1)  
- **npm** (v10.2.4)  

## 📦 Installation and Setup


1. Clone the repository:

   ```bash
   git clone https://github.com/VaishaliA12/CodeSync.git
   cd CodeSync

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a .env file in the root directory of the project and add the following environment variable:

   ```bash
   REACT_APP_BACKEND_URL=http://localhost:5000

4. To start the Client (Frontend), run:

   ```bash
   npm start

5. To start the Server (Backend), run:

   ```bash
   npm run server:dev
