# 🌐 SocialAppMERN

**📅 Date:** January 1, 2025

Welcome to **SocialAppMERN**, a project created to experiment with and learn the MERN (MongoDB, Express.js, React.js, Node.js) stack. This repository follows a tutorial from [GeeksforGeeks: Social Media Platform Using MERN Stack](https://www.geeksforgeeks.org/social-media-platform-using-mern-stack/) to build a basic social media platform.

---

## ✨ Features

- 📝 **Post Creation, Deletion, and Display**: Users can create posts, view all posts, and delete them.
- 🏗️ **Client-Server Architecture**: Follows a structured approach with a React frontend and Node.js/Express backend.

---

## 🛠️ Technologies Used

- ⚛️ **Frontend**: React.js
- 🌐 **Backend**: Node.js, Express.js
- 🗃️ **Database**: MongoDB
- 🎨 **Styling**: CSS or a CSS framework (if applied)

---

## 🚀 Installation and Setup

1. **📂 Clone the Repository**:
   ```bash
   git clone https://github.com/1202DREAMSCAPE/SocialAppMERN.git
   cd SocialAppMERN
   ```

2. **📦 Install Dependencies**:
   - For the backend:
     ```bash
     cd backend
     npm install
     ```
   - For the frontend:
     ```bash
     cd ../frontend
     npm install
     ```

3. **🔑 Environment Variables**:
   Create a `.env` file in the `backend` directory with the following details:
   ```env
   PORT=5000
   MONGO_URI=<Your MongoDB Connection String>
   ```

4. **▶️ Run the Application**:
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend development server:
     ```bash
     cd ../frontend
     npm start
     ```

5. **🌍 Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

---

## 📂 Project Structure

```
SocialAppMERN/
│
├── backend/           # Node.js and Express.js backend
│   ├── models/        # Mongoose schemas
│   ├── routes/        # API routes
│   └── server.js      # Main server file
│
├── frontend/          # React.js frontend
│   ├── src/
│   │   ├── components/  # React components
│   │   ├── pages/       # Application pages
│   │   └── App.js       # Main React app file
│   └── public/         # Public assets
│
└── README.md          # Project documentation
```

---

## 📚 Resources

- **GeeksforGeeks Tutorial**: [Social Media Platform Using MERN Stack](https://www.geeksforgeeks.org/social-media-platform-using-mern-stack/)
- **MERN Documentation**:
  - 🍃 [MongoDB](https://www.mongodb.com/docs/)
  - 🚀 [Express.js](https://expressjs.com/)
  - ⚛️ [React.js](https://reactjs.org/)
  - 🌐 [Node.js](https://nodejs.org/)

---

## 🎯 Goals and Learnings

This project serves as an introduction to the MERN stack. Through this, I aim to:

1. 🧠 Understand the architecture of full-stack applications.
2. ✍️ Gain hands-on experience with MongoDB, Express.js, React.js, and Node.js.
3. 🔗 Learn how to integrate frontend and backend systems effectively.

---

## 🛠️ Future Improvements

- 🔒 Add user authentication for login and signup.
- 🧑‍💼 Implement user profile management.
- 🎨 Enhance the UI/UX with better designs and animations.
