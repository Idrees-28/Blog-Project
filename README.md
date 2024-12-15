# Blog Project

## Project Overview
The Blog Project is a full-stack web application built using the MERN stack (MongoDB, Express, React, and Node.js). It enables users to create, view, edit, and delete blog posts. With features like user authentication, rich text editing, and a responsive design, this project serves as an excellent platform for learning or showcasing a full-stack implementation.

---

## Features
- **User Authentication**: Secure login and signup functionality.
- **Create and Manage Blogs**: Add, update, and delete blog posts.
- **Rich Text Editor**: Write and format blog content with ease.
- **Responsive Design**: Optimized for mobile, tablet, and desktop screens.
- **Dynamic Routes**: Blog posts are accessible through unique URLs.
- **Search Functionality**: Search blogs by title or content.

---

## Technologies Used

### Frontend
- **React**: For building the user interface.
- **Axios**: For making API requests.
- **React Router**: For navigation and routing.
- **CSS / Tailwind CSS**: For styling and responsive design.

### Backend
- **Node.js**: For server-side scripting.
- **Express**: For building RESTful APIs.
- **MongoDB**: For data storage.
- **Mongoose**: For object modeling and database interaction.
- **JWT (JSON Web Tokens)**: For secure user authentication.

---

## Installation Guide

### Prerequisites
- Node.js (v16 or later)
- MongoDB installed locally or access to a cloud-based MongoDB instance
- A modern web browser
- A code editor (optional for modifications)

---

### Steps

#### 1. Clone the Repository:
   ```bash
   git clone https://github.com/Idrees-28/blog-project.git
   ```

#### 2. Navigate to the Project Directory:
   ```bash
   cd blog-project
   ```

#### 3. Install Dependencies:

   **For Backend:**
   ```bash
   cd backend
   npm install
   ```

   **For Frontend:**
   ```bash
   cd frontend
   npm install
   ```

#### 4. Configure Environment Variables:
Create a `.env` file in the `backend` directory and add the following:
   ```
   PORT=5000
   DB_URI=your_database_connection_string
   JWT_SECRET=your_jwt_secret
   ```

#### 5. Start the Application:

   **Start the Backend:**
   ```bash
   cd backend
   npm start
   ```

   **Start the Frontend:**
   ```bash
   cd frontend
   npm start
   ```

#### 6. Open the App:
   Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## API Endpoints

### Authentication
- **POST /auth/signup**: Register a new user.
- **POST /auth/login**: Authenticate a user.

### Blogs
- **GET /blogs**: Retrieve all blogs.
- **GET /blogs/:id**: Retrieve a single blog by its ID.
- **POST /blogs**: Create a new blog.
- **PUT /blogs/:id**: Update an existing blog.
- **DELETE /blogs/:id**: Delete a blog.

---

## Contribution Guidelines
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## Acknowledgments
- **React**: For building the frontend.
- **Node.js**: For backend development.
- **Express**: For creating REST APIs.
- **MongoDB**: For database management.
- **JWT**: For secure user authentication.

---

## Contact
For any inquiries, feel free to reach out:
- **Email**: idreesjee2810@gmail.com
- **GitHub**: [Idrees-28](https://github.com/Idrees-28)

---
