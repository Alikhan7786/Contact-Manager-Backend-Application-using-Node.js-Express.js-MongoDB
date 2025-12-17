**Contact Manager Backend Application**

This project is a RESTful backend application developed using Node.js, Express.js, and MongoDB. It provides APIs to manage contact information by performing basic CRUD (Create, Read, Update, Delete) operations. The application follows a modular structure with separate files for routes, controllers, models, and database configuration.

**Features**

Create a new contact

Retrieve a contact by ID

Update existing contact details

Delete a contact

MongoDB integration using Mongoose

Environment variable support using dotenv

**Technologies Used**

Node.js

Express.js

MongoDB

Mongoose

Postman (for API testing)

**Project Structure**

app.js – Main entry point of the application

routes/ – Defines API routes

controllers/ – Contains business logic for each route

model/ – Defines the MongoDB schema

config/ – Database connection configuration

.env – Stores environment variables

.gitignore – Ignores node modules and environment files

**Installation and Setup**

Clone the repository

Install dependencies using npm install

Create a .env file and add your MongoDB connection string

Start the server using npm start

The server will run on http://localhost:5000.

**API Endpoints**

POST /api/contacts – Create a new contact

GET /api/contacts/:id – Get contact by ID

PUT /api/contacts/:id – Update contact details

DELETE /api/contacts/:id – Delete a contact

**Sample Request Body**
{
  "name": "John Doe",
  "email": "john@example.com",
  "phone": "9876543210"
}

**Purpose of the Project**

This project was developed to understand backend application development using Node.js and MongoDB, including REST API design, database integration, and server-side logic implementation.

**Author**

Developed by  **HARSHAD ALI KHAN**
