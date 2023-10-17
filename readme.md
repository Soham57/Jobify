# Jobify - Job Tracking Made Easier

Jobify is a MERN (MongoDB, Express.js, React, Node.js) application designed to simplify job tracking and management. It features a modern and intuitive user interface, efficient data handling, authentication, authorization, and a host of other functionalities.

## Project Overview

This project encompasses the creation of a React front-end application from scratch using VITE, setting up a server application with Express.js, configuring MongoDB in the cloud (Atlas), and integrating various modules and packages.

### Front-End (./client)

- Created a React front-end application using VITE.
- Added global styles to the React application.
- Built attractive and functional pages including Landing, Error, Register, Dashboard, etc.
- Set up routing using React Router 6.4+.
- Integrated nice-looking images and utilized them across the application.
- Configured a proxy in VITE for server communication.
- Implemented navigation using React Router 6 and nested pages.
- Integrated dayjs for handling date and time.
- Implemented search/filter functionality and pagination in the front-end.
- Created mock data using Mockaroo to populate the database.
- Utilized charts and cards for better visualization of data.
- Implemented logout functionality and secured routes.

### Back-End

- Created the server application from scratch using Express.js.
- Utilized ES6 Modules for better code organization and readability.
- Set up MongoDB database in the cloud using Atlas.
- Implemented routes and controllers for user authentication, job management, and more.
- Used 'express-async-errors' package for handling asynchronous errors gracefully.
- Integrated 'nodemon' for automatic server restarts during development.
- Implemented error handling in Express for a robust server-side application.
- Implemented hash password and validation layer using 'express-validator'.
- Used JWT for authentication and authorization.
- Set up permissions on the server to control access to resources.
- Created mock data and populated the database for testing and development.
- Implemented various Axios configurations for efficient HTTP requests.

## Benefits and Use Cases

Jobify provides several benefits to both job seekers and recruiters, making job tracking and management easier and more efficient.

### For Job Seekers

- **Efficient Job Tracking**: Jobify allows job seekers to easily track the jobs they've applied for, their progress, and other relevant details in a centralized and organized manner.

- **User-Friendly Interface**: The user-friendly interface of Jobify ensures a seamless experience for users, enabling them to focus more on their job applications rather than struggling with the application.

- **Advanced Search and Filters**: Jobify offers advanced search and filter functionalities, allowing users to narrow down their job search based on specific criteria such as location, job type, and company.

- **Visual Data Representation**: Charts and cards provide visual representation of job-related data, enabling users to quickly grasp their job application statistics and progress.

## File Structure

The project follows a well-organized file structure to maintain clarity and modularity.

- **client/**: React front-end application (source in `src/`, static assets in `public/`).
- **controllers/**: Controllers for authentication, job, and user functionality.
- **errors/**: Custom error handling utilities.
- **middleware/**: Express.js middleware for authentication, error handling, and validation.
- **models/**: Mongoose models for the database.
- **routes/**: Express.js routes for different functionalities.
- **utils/**: Utility files for constants, mock data, password, and token handling.
- **populate.js**: Script to populate the database.
- **server.js**: Entry point for the server application.

## Getting Started

To set up and run the Jobify application, follow these steps:

1. Clone the repository to your local machine.

2. Navigate to the client directory and install the necessary dependencies:

   ```bash
   cd client
   npm install
   ```

3. Repeat the same for the root directory (server):

   ```bash
   cd ..
   npm install
   ```

4. Run the server:

   ```bash
   npm start
   ```

5. Run the client:

   ```bash
   cd client
   npm start
   ```

6. Access the application through a web browser.

## Contribution

Feel free to contribute to this project by submitting issues, suggesting enhancements, or creating pull requests. Your contributions are highly appreciated.
