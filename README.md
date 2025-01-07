# MERN Server

This project is a backend server for a MERN (MongoDB, Express, React, Node.js) application. It is built using TypeScript and includes essential configurations for development and production environments.

## Features

- **Express** for routing and middleware.
- **Mongoose** for MongoDB object modeling.
- **TypeScript** for type safety and enhanced development experience.
- Scripts for building, running, and seeding the application.

## Project Structure

. ├── src/ # Source files ├── dist/ # Compiled files (generated after build) ├── tsconfig.json # TypeScript configuration ├── package.json # Project dependencies and scripts └── node_modules/ # Installed npm packages


## Prerequisites

- **Node.js** (v16 or higher)
- **npm** (v8 or higher)
- **MongoDB** (running instance)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd mern-server
Install dependencies:
npm install
Configure environment variables:
Create a .env file in the project root and add the following (adjust values as necessary):

MONGO_URI=mongodb://localhost:27017/your-database-name
PORT=3000
Scripts

The following scripts are defined in package.json:

Build the project:
npm run build
Compiles the TypeScript source code into JavaScript files in the dist/ folder.
Start the server:
npm run start
Builds the project and starts the server from the dist/ folder.
Run in development mode:
npm run dev
Starts the server using nodemon with live reload during development.
Seed the database:
npm run seed
Runs the seed script to populate the database with sample data.
Development

TypeScript Configuration
tsconfig.json specifies:
src/ as the root directory for TypeScript files.
dist/ as the output directory for compiled JavaScript files.
Nodemon Configuration
Watches for changes in src/ files.
Automatically compiles and restarts the server during development.
Dependencies

Main
express: Web framework for Node.js.
mongoose: MongoDB object modeling.
Development
typescript: TypeScript compiler.
@types/express: Type definitions for Express.
@types/node: Type definitions for Node.js.
dotenv: Environment variable management.
How to Run

Start the MongoDB server.
Build and start the project:
npm run start
Access the server at http://localhost:3000.
License
