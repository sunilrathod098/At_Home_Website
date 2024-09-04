# Frontend Overview

This directory contains the frontend code for the **AT_Home_Website** project. The frontend is built using HTML, CSS, and JavaScript.

## Structure

- **index.html**: The main entry point of the website.
- **styles.css**: The global stylesheet for the website.
- **script.js**: The main JavaScript file for handling client-side logic.
- **assets/**: This folder should contain images, fonts, and other media assets used in the frontend.
- **components/**: (Optional) You can create this folder to organize reusable components like headers, footers, or modals.

## Development Guidelines

1. **Branching**: Create a new branch for each feature or page you're working on. Name it according to the feature (e.g., `feature/homepage-design`).
2. **Styling**: Follow a consistent naming convention for classes and IDs in your CSS. Use the BEM (Block Element Modifier) naming convention for clarity.
3. **JavaScript**: Keep your JavaScript modular. If needed, split different functionalities into separate files and include them in `index.html`.
4. **Responsiveness**: Ensure that all pages are responsive across different devices (mobile, tablet, desktop).

## How to Contribute

### Step 1: Install Required Software
Before you begin, make sure you have the following installed on your computer:

1. **Git**: [Download Git](https://git-scm.com/downloads) and install it.
   - Git is a version control system that allows you to track changes and collaborate with others.
2. **Code Editor**: Install [Visual Studio Code (VS Code)](https://code.visualstudio.com/).
   - This is the code editor you'll use to write and edit your code.

### Step 2: Clone the Repository
1. Open Git Bash (Windows) or your terminal (Mac/Linux).
2. Navigate to the directory where you want to save the project:
   ```bash
   cd path/to/your/directory
Clone the project repository from GitHub:
git clone https://github.com/YourUsername/AT_Home_Website.git
This will download a copy of the project to your local machine.

Step 3: Navigate to the Frontend Directory
After cloning the repository, navigate to the frontend directory:
cd AT_Home_Website/frontend

Step 4: Open the Project in VS Code
Open VS Code.
Click on File > Open Folder and select the frontend directory from the project.

Step 5: Start Developing
HTML: Open and edit index.html.
CSS: Open and edit styles.css.
JavaScript: Open and edit script.js.

Step 6: Preview Your Work
To see your changes:
Right-click on index.html in VS Code.
Select "Open with Live Server" (you may need to install the Live Server extension from the VS Code marketplace).

Step 7: Commit and Push Your Changes to GitHub
After making changes, save your files in VS Code.
In Git Bash/Terminal, check the status of your changes:
git status

Stage your changes:
git add .

Commit your changes with a message:
git commit -m "Your message here"

Push your changes to GitHub:
git push origin main

Branching:
Always work on a new branch when starting a new feature:

Create a new branch:
git checkout -b feature-branch-name

Push the branch to GitHub:
git push origin feature-branch-name

**Notes**
Keep all images and other assets in the assets/ folder.
For any questions, please reach out to **KRISHNA**(team lead)
