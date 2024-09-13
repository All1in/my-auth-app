# Registration and Login Form with Admin Panel

This project is a basic user authentication system built with React for the frontend and Node.js for the backend (optional). It provides functionality for user registration, login, and an admin panel for updating user credentials. The frontend consists of a registration and login form, and upon successful login, users can access an admin panel where they can view and update their profile information.

# Tech Stack

Frontend: 

1. React(Vite)
2. Redux
3. sass

Backend:

1. express
2. mongoose
3. nodemon
4. mongodb

# Features
## Registration:

Email and password validation
Password requirements: 6-20 characters, at least one lowercase letter, one uppercase letter, one number, and one special character (but not at the start or end).
Sends registration request to the server.
On successful registration, redirects user to the login page.

## Login:

Validates email and password.
Redirects to admin panel upon successful login.

## Admin Panel:

Displays user’s image, email, and password.
Allows the user to update their email and password.


# Validation Rules
## Registration Form:
Email: Must be a valid email address.
## Password:
Minimum length: 6 characters.
Maximum length: 20 characters.
Must contain:
At least one lowercase letter.
At least one uppercase letter.
At least one number.
At least one special character.
A special character cannot be at the beginning or the end of the password.
## Login Form:
Email: Must be a valid email address.
Password: Basic password input.