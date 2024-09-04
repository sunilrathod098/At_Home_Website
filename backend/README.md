# Backend Overview

This directory contains the backend code for the **AT_Home_Website** project. The backend is built using Node.js, Express, and MySQL. It handles server-side logic, database interactions, and API endpoints.

## Structure

- **index.js**: The main entry point of the backend application.
- **routes/**: Contains all the route files for handling different API endpoints.
  - **routes.js**: Defines the routes and maps them to the respective controllers.
- **controllers/**: Contains the logic for processing requests and interacting with the database.
  - **registerController.js**: Handles user registration logic.
  - **loginController.js**: Manages user login functionality.
- **models/**: (Optional) You can create this folder to define database schemas and ORM models.
- **config/**: Contains configuration files for the application.
  - **db.js**: Manages the database connection setup.
- **middlewares/**: (Optional) Custom middleware functions for tasks like authentication, error handling, etc.
- **public/**: (Optional) Serves static files like images, CSS, and JavaScript that are shared across the application.
- **package.json**: Contains the metadata for the project and lists all the dependencies.
- **package-lock.json**: Records the exact versions of installed packages for consistency across different environments.

## Development Guidelines

1. **Branching**: Create a new branch for each feature or bug fix you're working on. Name it according to the feature or fix (e.g., `feature/authentication`, `fix/login-issue`).
2. **Coding Standards**: Follow consistent coding standards such as naming conventions, code formatting, and proper documentation. Use ESLint for maintaining code quality.
3. **Database Interaction**: Keep all database queries modular and organized. Use prepared statements or ORM (e.g., Sequelize) to interact with the database securely.
4. **Environment Variables**: Store sensitive information like database credentials in an `.env` file. Make sure `.env` is included in `.gitignore` to avoid committing it to the repository.

## Project Setup

### Step 1: Install Required Software

Before you begin, ensure you have the following installed on your computer:

1. **Node.js**: [Download Node.js](https://nodejs.org/en/download/) and install it.
   - Node.js is the runtime that allows you to run JavaScript code server-side.
2. **MySQL**: Install MySQL and set up a local or remote MySQL database.
   - MySQL is the database management system used for storing data.

### Step 2: Clone the Repository

1. Open Git Bash (Windows) or your terminal (Mac/Linux).
2. Navigate to the directory where you want to save the project:
   ```bash
   cd path/to/your/directory

3. Clone the project repository from GitHub:
git clone https://github.com/YourUsername/AT_Home_Website.git
This will download a copy of the project to your local machine.

Step 3: Navigate to the Backend Directory
After cloning the repository, navigate to the backend directory:
cd AT_Home_Website/backend

Step 4: Install Dependencies
Install the required Node.js packages listed in package.json:
npm install

Step 5: Set Up the Environment Variables
Create a .env file in the backend directory to store environment-specific variables such as database credentials:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=athome_db
PORT=3000

Step 6: Initialize the Database
Create the required database in MySQL:
CREATE DATABASE athome_db;
Run any migration or seed scripts if available to set up the database schema and initial data.

Step 7: Start the Development Server
Start the backend server by running:
npm start
The server will start on the port defined in the .env file (default is 3000).
Access the application in your browser at http://localhost:3000.

Step 8: Commit and Push Your Changes to GitHub
After making changes, save your files in your code editor.
In Git Bash/Terminal, check the status of your changes:
git status
Stage your changes:
git add .
Commit your changes with a message:
git commit -m "Your message here"
Push your changes to GitHub:
git push origin main


Branching
Always work on a new branch when starting a new feature or fixing an issue:
Create a new branch:
git checkout -b feature-branch-name
Push the branch to GitHub:
git push origin feature-branch-name

**Notes**
Keep your code modular and organized for maintainability.
Ensure your routes and controllers are properly documented.
For any questions or issues, please reach out to **KRISHNA** (team lead).




