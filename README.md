# MERN Stack Food Ordering App

This repository contains the source code for a Food Ordering App developed using the MERN (MongoDB, Express.js, React, Node.js) stack. The application allows users to browse a variety of food items, add them to the cart, and place orders. The backend server is built with Node.js and Express, MongoDB is used as the database, and the frontend is developed using React.

## Features

- **User Authentication:** Users can create accounts, log in, and authenticate their sessions.
- **Browse Menu:** Users can explore a variety of food items available in the menu.
- **Shopping Cart:** Users can add items to their cart and view the selected items before placing an order.
- **Place Orders:** Users can place orders, view order history, and track the status of their orders
  
## Technologies Used

- **Frontend:**
  - React: JavaScript library for building user interfaces.
  - React Router: Routing library for navigating between components.
  - Axios: HTTP client for making API requests.

- **Backend:**
  - Node.js: JavaScript runtime for server-side development.
  - Express.js: Web application framework for Node.js.
  - MongoDB: NoSQL database for storing application data.
  - Mongoose: MongoDB object modeling tool.

- **Authentication:**
  - JSON Web Tokens (JWT): For secure authentication and authorization.

## Getting Started

Follow these steps to set up and run the MERN Stack Food Ordering App locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/mern-food-ordering-app.git
   cd mern-food-ordering-app
This repository contains the source code for a Food Ordering App developed using the MERN (MongoDB, Express.js, React, Node.js) stack. The application allows users to browse a variety of food items, add them to the cart, and place orders. The backend server is built with Node.js and Express, MongoDB is used as the database, and the frontend is developed using React.

### Install Dependencies:
For the frontend:

``` bash

cd client
npm install
```
For the backend:

```bash
cd server
npm install
```
### Configure Environment Variables:
```Create a .env file in the server directory and add the necessary environment variables (e.g., MongoDB connection URI, JWT secret, etc.)```

## Run the Application:
For the backend:

```bash
cd server
npm start
```
For the frontend:
```bash
cd client
npm start
```
Open your browser and navigate to http://localhost:3000 to access the Food Ordering App.

## Project Structure

- `client`: Houses the frontend code developed with React.js.
- `server`: Encompasses the backend code implemented with Node.js.
  - `models`: Holds MongoDB models for defining data schema.
  - `routes`: Manages Express routes for handling API requests.
  - `controllers`: Contains the logic for handling business operations.
  - `config`: Stores configuration files, such as the database connection setup.
  - `middleware`: Includes custom middleware for route protection and authentication.
  - `public`: Houses static assets used in the application.
