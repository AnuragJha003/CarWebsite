# Car Management Application

This is a Car Management Application built using the MERN stack (MongoDB, Express, React, Node.js). Users can register, log in, and manage their cars, including adding, updating, deleting, and viewing cars with details such as images, title, description, and tags.

## Features

- **User Authentication**: Sign up and log in.
- **Add Car**: Users can add a car with images, title, description, and tags.
- **View Car**: Users can view the exisiting car details.
- **Manage Cars**: List, view, edit, and delete cars.
- **Search**: Search cars by title, description, or tags.
- **Delete**: Delete the car as required.
- **Update**: Update the car details and modify.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT, bcryptjs

## API Endpoints

- `POST /api/auth/signup` - Create a new user
- `POST /api/auth/login` - User login
- `POST /api/products` - Create a new car
- `GET /api/products` - Get all cars for logged-in user
- `GET /api/products/:id` - Get car details
- `PUT /api/products/:id` - Update a car
- `DELETE /api/products/:id` - Delete a car
- `GET /api/products/search` - Search cars

## Setup Instructions

### Backend (Server Side)

1. Clone the repository and start the backend server:
   ```bash
   git clone [<repo_url>](https://github.com/AnuragJha003/CarWebsite)
   cd [<repo_name>](https://github.com/AnuragJha003/CarWebsite)/server
   npm install 
   npm start
   ```
2. Start the frontend:
   ```bash
   git clone [<repo_url>](https://github.com/AnuragJha003/CarWebsite)
   cd [<repo_name>](https://github.com/AnuragJha003/CarWebsite)/client
   npm install 
   npm run dev
   ```

