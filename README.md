## VRV Security Frontend Assignment

This repository contains the frontend code for my project developed as part of the VRV Security assignment for the Frontend Intern position. This project is built using React.js and focuses on creating a user-friendly and responsive Role-Based Access Control (RBAC) interface.

## Project Overview

The RBAC UI is designed to help administrators manage users, roles, and permissions, offering functionalities to:

- Create, edit, and delete users
- Assign roles and permissions dynamically to users
- Search and filter users 

## Features

1. ### Dashboard:
   View a comprehensive overview of users and their roles in the system.
2. ### Manage Users:
   Add, edit, and delete users while managing their status (Active/Inactive).
3. ### Manage Roles:
   Define new roles, edit existing roles, and delete roles as necessary.
4. ### Manage Permissions:
   Assign and modify permissions for roles dynamically.
5. ### Search and Filter:
   Search for users based on their name or email and filter them as needed.

## Technologies Used

- React.js for building the user interface.
- React Router for managing routing across different pages.
- Styled-components for CSS-in-JS styling.
- Context API to manage global state (e.g. theme management).

## Getting Started

To get started with this project, follow the steps below:

### 1. Clone the Project 
   First, clone the repository to your local machine using command :
     
    git clone https://github.com/janhvi-pandey/VRV-Security-Frontend-Assignment.git
        


### 2. Navigate to the Project Folder
   Move into the project directory:

    - cd VRV-Security-Frontend-Assignment/ 
    - cd frontend/


### 3. Install Dependencies
   Install all the required dependencies using npm:

    npm install
  
### 4. Start the Application
   Run the development server:

    npm start


This will start the app on http://localhost:3000. You should be able to access the application in your browser.

## Contact Information

If you encounter any issues or need further clarification, feel free to contact me at:

- Email: narendravasa242003@gmail.com
- Phone: +91 9059346489

## Folder Structure

- frontend *(Folder)*
  - .gitignore *(File)*
  - package-lock.json *(File)*
  - package.json *(File)*
  - public *(Folder)*
  - src *(Folder)*
    - App.js *(File)*
    - App.test.js *(File)*
    - components *(Folder)*
      - adminpanel *(Folder)*
        - Dashboard.js *(File)*
        - managepermission *(Folder)*
          - AddPermission.js *(File)*
          - Permission.js *(File)*
        - manageroles *(Folder)*
          - AddRole.js *(File)*
          - ManageRole.js *(File)*
        - manageusers *(Folder)*
          - AddUser.js *(File)*
          - EditUser.js *(File)*
          - ManageUsers.js *(File)*
      - authentication *(Folder)*
        - SignIn.js *(File)*
        - SignUp.js *(File)*
      - common *(Folder)*
        - Footer.js *(File)*
        - Navbar.js *(File)*
        - Sidebar.js *(File)*
        - SmallscreenSidebar.js *(File)*
      - context *(Folder)*
        - ThemeContext.js *(File)*
    - index.css *(File)*
    - index.js *(File)*
    - logo.svg *(File)*
    - media *(Folder)*
    - reportWebVitals.js *(File)*
    - setupTests.js *(File)*

