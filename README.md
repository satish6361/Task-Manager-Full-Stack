# Task Manager Application

This is a Task Manager Application built using the MERN stack (MongoDB, Express, React, Node.js). The application allows users to manage their tasks efficiently by providing features to add, view, edit, and delete tasks.

## Features

### Front-end

1. **Landing Page**: Displays a list of all tasks.
2. **Add New Tasks**: Users can add new tasks with a title, description, and due date.
3. **View Task Details**: Users can view detailed information of each task.
4. **Edit Tasks**: Users can edit existing tasks.
5. **Delete Tasks**: Users can delete tasks.
6. **Responsive Design**: Ensures usability on both desktop and mobile devices.

### Back-end

1. **RESTful API**: Handles CRUD operations for tasks.
2. **API Endpoints**:
   - `GET /tasks`: Retrieve all tasks.
   - `POST /tasks`: Create a new task.
   - `GET /tasks/:id`: Retrieve a single task by its ID.
   - `PUT /tasks/:id`: Update an existing task.
   - `DELETE /tasks/:id`: Delete a task.

## Technologies Used

- **Front-end**: React, HTML, CSS, JavaScript
- **Back-end**: Node.js, Express
- **Database**: MongoDB
- **Styling**: Styled-components

## Installation and Setup

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js
- npm or yarn
- MongoDB

### Clone the Repository

```bash
git clone https://github.com/yourusername/task-manager.git
cd task-manager


### Set Up the Back-end
Navigate to the backend directory:

bash
Copy code
cd backend
Install the dependencies:

bash
Copy code
npm install
Create a .env file in the backend directory and add your MongoDB URI and any other necessary environment variables:

env
Copy code
MONGODB_URI=your_mongodb_connection_string
Start the backend server:

bash
Copy code
npm start
The backend server should now be running on http://localhost:4000.

Set Up the Front-end
Navigate to the frontend directory:

bash
Copy code
cd ../frontend
Install the dependencies:

bash
Copy code
npm install
Start the front-end development server:

bash
Copy code
npm start
The front-end application should now be running on http://localhost:3000.
