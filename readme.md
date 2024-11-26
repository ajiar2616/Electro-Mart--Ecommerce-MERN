# Electro Mart (MERN E-commerce)

Electro Mart is a robust MERN stack-based e-commerce web application tailored for mechanical and electronic product stores.

---

## Features

- **Authentication:** Secure JWT-based login system
- **User Roles:** Admin dashboard and user dashboard
- **User Profile Management:** View and update profiles
- **Product Management:** Search, add, view, update, and delete products and categories
- **Admin Controls:** Manage users, products, and categories with dedicated admin privileges
- **Private Routing:** Secure access to sensitive routes

---

## Tech Stack

#### Client:
- React.js
- CSS3

#### Server:
- Node.js
- Express.js

#### Database:
- MongoDB

---

## Run Locally

#### Clone the Repository
Clone the project repository to your local machine:
```bash
git clone https://github.com/NaveenMathramkott/MERN_Ecommecre.git
```

## Set Up Environment Variables
Create a `.env` file in both the `server` and `client` directories and add the following configurations:

#### Server (`/server/.env`)
```bash
PORT=your_server_port
DEV_MODE=development
MONGO_URL=your_mongo_connection_string
JWT_SECRET_KEY=your_jwt_secret_key
```

#### Client (`/client/.env`)
```bash
REACT_APP_BASE_URL=your_api_base_url
```

## Navigate to the Project Directory
```bash
cd MERN_Ecommecre
```

## Install Dependencies

#### Server Dependencies
```bash
cd server
npm install
```

#### Client Dependencies
```bash
cd client
npm install
```

## Start the Application

#### Start the Server
```bash
cd server
npm run start
```

#### Start the Client
```bash
cd client
npm start
```

---


## Access the Application
Once both the server and client are running:

- Open your browser and navigate to `http://localhost:3000` to access the client application.
- The server will run on `http://localhost:<PORT>` based on the environment configuration.
