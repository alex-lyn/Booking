# ****Booking Application****

This project is a Booking application created using a modern React stack with Vite as a build tool. It includes routing,
state management, and form handling to interact with a JSON server and display hotel data dynamically. The application
consists of three main pages:

1. Main: The homepage of the application.
2. About: Provides information about the application.
3. Hotels: Displays a list of hotels based on form submissions.

## **Project Stack and Tools**

* Vite: Build tool for faster development.
* React: Frontend library for building the UI.
* React-router: Used for routing between pages.
* React-final-form: For form handling and validation.
* MUI (Material-UI): Component library for styling and UI elements.
* Axios: For making HTTP requests to the JSON server.
* Redux: State management library.
* Redux-first-history: Integration for handling browser history with Redux.
* Redux-saga: Middleware for managing side effects.
* ENV: Environment variable management.
* Eslint: Linting for consistent code style.
* Json-server: Local server for simulating backend API.

## Project Features

#### Form Handling: 
The "Main" page contains a form where users can select a destination from a server-provided list (db.json).

#### Data Submission: 
Upon form submission, the data is validated, and a request is made to json-server to fetch a list of 
hotels. Form data is sent through the request payload.

#### Page Redirection: 

After a successful response, users are redirected to the "Hotels" page where the list of hotels is
displayed.

## Installation and Running the Project

Prerequisites
Make sure you have Node.js installed (version 18.16.0 or higher).

### Setup

1. Clone the repository.
2. Install dependencies: npm install
3. Create a .env file in the project root and configure the required environment variables.

## Scripts

### Start Development Server:

npm run dev - This runs both the Vite server and json-server concurrently, with the JSON server watching db.json at port 3000.

### Build:

npm run build
Creates an optimized build of the application.
