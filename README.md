# React Multi-Page Application with Video Card Component

A responsive multi-page React application with authentication and video card components, built with React Router and TailwindCSS.

## Features

- Responsive design that works on all screen sizes
- Login page with form validation
- Protected routes with authentication
- YouTube video embedding
- Dynamic title and description
- Call-to-action buttons with hover effects
- TailwindCSS styling
- React Router for navigation

## Quick Start

### Option 1: Using the setup script

Simply run the setup script:

```
setup.bat
```

This will install all dependencies and start the development server.

### Option 2: Manual setup

1. Install dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm start
   ```

## Project Structure

- `src/components/LoginPage.jsx` - Login form with validation
- `src/components/VideoPage.jsx` - Page displaying video cards
- `src/components/VideoCard.jsx` - The main card component
- `src/components/Navbar.jsx` - Navigation bar with logout functionality
- `src/components/ProtectedRoute.jsx` - Authentication wrapper
- `src/components/NotFoundPage.jsx` - 404 page
- `src/components/LoadingSpinner.jsx` - Loading indicator
- `src/App.jsx` - Main application with routing
- `src/index.js` - Entry point
- `src/index.css` - TailwindCSS imports
- `public/index.html` - HTML template

## Using the Application

1. Start at the login page
2. Enter a valid email and password (at least 6 characters)
3. After successful login, you'll be redirected to the video page
4. Use the navbar to log out and return to the login page