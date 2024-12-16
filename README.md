# Twitter Clone Web Application

## Project Overview
This project is a full-stack Twitter-inspired web application that enables users to post tweets, interact in real time, and follow other users. The project showcases real-time functionality, secure authentication, and responsive design, delivering an experience similar to Twitter.

## Introduction
The Twitter Clone application replicates core features of Twitter, including user authentication, tweet posting, live updates, and following other users. Built using modern front-end and back-end technologies, this project demonstrates proficiency in full-stack development, real-time communication, and database management.

---

## Project Features
### User Features
- **User Authentication**:
  - Secure JWT-based login, registration, and session management.
- **Tweet Management**:
  - Post, edit, delete, and view tweets.
  - View tweets from users they follow in real time.
- **User Interactions**:
  - Follow/unfollow users.
  - Like tweets and view engagement metrics.
- **Real-Time Updates**:
  - Live updates for new tweets, likes, and follows using **Socket.io**.

### Performance and Design
- **Responsive Design**:
  - Built with a mobile-first approach, ensuring a seamless user experience across all devices.
- **Real-Time Communication**:
  - Integrated WebSocket support with **Socket.io** for instant updates.
- **Scalable APIs**:
  - Optimized backend APIs to handle concurrent requests efficiently.

---

## Software Tools and Technologies

### Frontend
- **React.js**: Component-based library for building dynamic and interactive UIs.
- **React Router**: Enables client-side routing for a smooth navigation experience.
- **CSS**: Custom styling for responsive and clean design.

### Backend
- **Node.js**: JavaScript runtime environment for server-side operations.
- **Express.js**: Lightweight framework for building RESTful APIs.

### Database
- **MongoDB**: NoSQL database for storing user and tweet data.
- **Mongoose**: ODM library for interacting with MongoDB.

### Real-Time Communication
- **Socket.io**: Enables WebSocket-based real-time updates for tweets and interactions.

### Authentication
- **JWT**: Secure JSON Web Tokens for user authentication and authorization.

### Development Tools
- **Vite**: Build tool for fast development and optimized production builds.
- **Nodemon**: Backend development tool for monitoring changes in real time.

---

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hajeeong/Twitter_clone.git
   cd Twitter_clone
   ```

2. **Install Dependencies**:
   Navigate to the `frontend` and `backend` directories and install the required packages:
   ```bash
   npm install
   ```

3. **Set Environment Variables**:
   Create a `.env` file in the `backend` directory with the following variables:
   ```plaintext
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ````

4. **Run the Backend**:
   ```bash
   cd backend
   npm start
   ```

5. **Run the Frontend**:
   ```bash
   cd frontend
   npm run dev
   ```

6. **Access the Application**:
   Open `http://localhost:5173` in your browser.

---

## Screenshots
![Login Page](link_to_login_screenshot)
![Home Page](link_to_homepage_screenshot)

---

## Conclusion
This Twitter Clone project highlights essential features of a social media platform, including real-time communication, dynamic UI components, and secure authentication. Built with a modern tech stack, it demonstrates the ability to design and develop scalable full-stack applications that provide an interactive user experience.
