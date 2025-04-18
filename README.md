
# Task Manager Application

Welcome to the Task Manager Application! This is a full-stack web application built to help you manage your tasks efficiently. It includes user authentication (login/register), a task dashboard, task creation, editing, filtering, and deletion features. The frontend is developed using React, and the backend is powered by a Node.js/Express server with a MongoDB database.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- User authentication with login and registration.
- Create, edit, delete, and toggle the status of tasks.
- Filter tasks by title, category, and status.
- Responsive dashboard displaying total, pending, and completed tasks.
- Stunning dark-themed UI with 3D effects and animations.
- Secure API endpoints with token-based authentication.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14.x or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [MongoDB](https://www.mongodb.com/) (local or remote instance)
- [Git](https://git-scm.com/) (for cloning the repository)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/task-manager.git
   cd task-manager
   ```

2. **Set Up the Backend**
   - Navigate to the backend directory:
     ```bash
     cd task-mng-back
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file in the `task-mng-back` directory and add the following (replace with your MongoDB URI):
     ```
     MONGODB_URI=mongodb://localhost:27017/taskmanager
     PORT=5000
     JWT_SECRET=your-secret-key
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Set Up the Frontend**
   - Navigate to the frontend directory:
     ```bash
     cd ../task-mng-front
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the frontend development server:
     ```bash
     npm start
     ```
   - Open your browser and visit `http://localhost:3000`.

## Usage
1. **Register a New Account**
   - Navigate to the registration page and create a new account with a username and password.
   
2. **Log In**
   - Use your credentials to log in and access the task management interface.

3. **Manage Tasks**
   - Add new tasks with a title, description, category, status, and priority.
   - Edit or delete existing tasks.
   - Filter tasks using the search, category, and status options.
   - Toggle task status between "pending" and "completed."

4. **Logout**
   - Click the "Logout" button to end your session.

## Project Structure
```
task-manager/
├── backend/          # Backend directory
│   ├── config/             # Configuration files
│   ├── controllers/        # API controllers
│   ├── models/             # Mongoose models
│   ├── routes/             # API routes
│   ├── .env                # Environment variables
│   ├── package.json
│   └── server.js
├── frontend/         # Frontend directory
│   ├── src/
│   │   ├── components/     # React components
│   │   │   ├── Auth.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── TaskFilter.jsx
│   │   │   ├── TaskForm.jsx
│   │   │   └── TaskList.jsx
│   │   ├── login.css       # Styling for Login
│   │   ├── register.css    # Styling for Register
│   │   ├── taskfilter.css  # Styling for TaskFilter
│   │   ├── taskform.css    # Styling for TaskForm
│   │   ├── tasklist.css    # Styling for TaskList
│   │   ├── App.jsx
│   │   ├── index.js
│   │   └── index.css
│   ├── package.json
│   └── public/
├── README.md
└── .gitignore
```

## Contributing
We welcome contributions to improve this project! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m "Add your message"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a detailed description of your changes.

Please ensure your code follows the existing style and includes appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or support, please open an issue on the [GitHub repository](https://github.com/rithik333r/task-manager/issues) or contact the maintainer at `ffrithik@gmail.com`.

---

