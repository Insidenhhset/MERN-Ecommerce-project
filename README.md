# MERN-Ecommerce-project

This project is an E-commerce application built using the MERN stack (MongoDB, Express, React, Node.js).

## Project Setup

To get started with the project, follow the steps below:

First, clone the repository, navigate to the project folder, install all dependencies, and configure the environment variables.


## Clone the repository
git clone https://github.com/Insidenhhset/MERN-Ecommerce-project.git

# Navigate to the project folder
cd MERN-Ecommerce-project

## Install backend dependencies
npm install

#3 If your frontend is in a separate folder, navigate to it and install frontend dependencies
cd client
npm install

## Navigate back to the project root
cd ..

## Create a .env file in the root directory and add the following environment variables:
.env
PORT=5000
MONGO_URI=YOUR_DB_URL
UPSTASH_REDIS_URL=YOUR_REDIS_URL
ACCESS_TOKEN_SECRET=secret
REFRESH_TOKEN_SECRET=secret
CLOUDINARY_CLOUD_NAME=YOUR_CLOUD_NAME
CLOUDINARY_API_KEY=YOUR_API_KEY
CLOUDINARY_API_SECRET=YOUR_API_SECRET
STRIPE_SECRET_KEY=YOUR_STRIPE_SECRET_KEY
CLIENT_URL=http://localhost:5173
NODE_ENV=development

```bash
