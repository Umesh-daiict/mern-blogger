# MERN Project README

Welcome to the MERN (MongoDB, Express, React, Node.js) project! This README provides an overview of the project structure and relevant details.

## Project Overview

This project follows the MERN stack architecture, combining both backend and frontend technologies. Here's a breakdown:

1. **Backend (Server) - Express and MongoDB:**
   - We've built the backend using Express.js, a popular Node.js framework.
   - MongoDB serves as our database, allowing us to store and retrieve data efficiently.
   - The backend follows the Model-View-Controller (MVC) pattern for organization.

2. **Frontend (Client) - React with Tailwind CSS:**
   - The frontend is developed using React, a powerful JavaScript library for building user interfaces.
   - We've chosen Tailwind CSS for styling, providing utility-first classes for rapid UI development.
   - React components are structured for reusability and maintainability.

## Project Structure

Here's how our project is organized:

```
mern-project/
├── backend/
│   ├── controllers/
│   │   ├── user.controller.js
│   │   └── ...
│   ├── models/
│   │   ├── user.model.js
│   │   └── ...
│   ├── routes/
│   │   ├── auth.route.js
│   │   └── ...
│   ├── index.js
│   └── ...
├── frontend/
│   ├── public/
│   │   ├── index.html
│   │   └── ...
│   ├── src/
│   │   ├── components/
│   │   │   ├── header.js
│   │   │   └── ...
│   │   ├── pages/
│   │   │   ├── home.js
│   │   │   └── ...
│   │   ├── App.js
│   │   └── ...
├── .gitignore
├── package.json
└── README.md
```

## Getting Started

1. **Clone the Repository:**
   ```
   git clone git@github.com:Umesh-daiict/mern-blogger.git
   cd mern-blogger
   ```

2. **Backend Setup:**
   - Navigate to the `backend` directory:
     ```
     cd backend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Set up your MongoDB connection in `server.js`.

3. **Frontend Setup:**
   - Navigate to the `frontend` directory:
     ```
     cd frontend
     ```
   - Install dependencies:
     ```
     npm install
     ```

4. **Run the Project:**
   - Start the backend server:
     ```
     npm run dev
     ```
   - Start the frontend development server:
     ```
     npm run dev
     ```

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Let's build something amazing together! 🚀

---
