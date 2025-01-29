# Blog Application

## Description
This is a Node.js-based blog application using Express.js, EJS templating engine, and MongoDB for data storage. The application includes user authentication with Passport.js and session management.

## Features
- User authentication (login and registration).
- Session handling with Express-Session.
- MongoDB database integration with Mongoose.
- Flash messaging using Express-Flash.
- File uploads using Multer.
- Templating with EJS and Express Layouts.
- Method override for RESTful operations

## Technologies Used
- Node.js.
- Express.js.
- MongoDB & Mongoose.
- Passport.js (for authentication).
- EJS (templating engine).
- Multer (for file uploads).
- dotenv (for environment variables)
- Express-session (session management)

## Installation
1. Clone the repository:
   ```sh
   git clone <repo-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd blog
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a `.env` file in the root directory and add:
   ```env
   SESSION_SECRET=your_secret_key
   MONGO_URI=your_mongodb_connection_string
   ```
5. Start the development server:
   ```sh
   npm run dev
   ```

## Usage
- Open a browser and navigate to `http://localhost:5000`.
- Register/Login to the application.
- Create, edit, or delete blog posts.

## Project Structure
```
blog/
