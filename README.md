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
MONGO_URI=mongodb+srv://ns1624752:qaUmeA6A2TbTQGb4@cluster0.23peu.mongodb.net/shopify_db?retryWrites=true&w=majority&appName=Cluster0
UPSTASH_REDIS_URL=rediss://default:AWmUAAIjcDE2MDYxZDRkNTY5OTQ0OWNlYTZkZDZhMzZhZmM5MDJmYnAxMA@smooth-ox-27028.upstash.io:6379
ACCESS_TOKEN_SECRET=secret
REFRESH_TOKEN_SECRET=secret
CLOUDINARY_CLOUD_NAME=dbhozx9sc
CLOUDINARY_API_KEY=941832551151181
CLOUDINARY_API_SECRET=CKcy3U2yHKZwcYmA7PFXrXRlNBg
STRIPE_SECRET_KEY=sk_test_51Mr3KXSCMO5XbVMsM87hC2CJjpzKn5RFTlI7YvcDEAmHvP4J8kmEVsYOucQkXoJ17JBCGDevrWqaxhWcxNlVSisP00OwUWbeSa
CLIENT_URL=http://localhost:5173
NODE_ENV=development

```bash
