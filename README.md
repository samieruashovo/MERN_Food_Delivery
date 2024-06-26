
# Installation
Follow these steps to get a local copy of the project up and running.

## Prerequisites
Make sure you have the following installed:

Node.js (https://nodejs.org/)
MongoDB (https://www.mongodb.com/)

# Backend
Clone the repository:

git clone (https://github.com/samieruashovo/MERN_Food_Delivery.git)

cd MERN_Food_Delivery

Install backend dependencies:

cd backend
npm install
Create a .env file in the backend directory and add your environment variables:

MONGODB_CONNECTION_STRING=mongodb+srv://


AUTH0_AUDIENCE=
AUTH0_ISSUER_BASE_URL=https://dev-


CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

FRONTEND_URL=http://localhost:5173
STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=
Start the backend server:

npm run dev
The backend server should be running on http://localhost:7000.

# Frontend
Navigate to the frontend directory:


cd ..
cd frontend

Install frontend dependencies:

npm install
Create a .env file in the frontend directory and add your environment variables:

VITE_API_BASE_URL=http://localhost:7000

VITE_AUTH0_DOMAIN=
VITE_AUTH0_CLIENT_ID=
VITE_AUTH0_CALLBACK_URL=http://localhost:5173
VITE_AUTH0_AUDIENCE=

Start the frontend development server:


npm start
The frontend server should be running on http://localhost:5173.

Usage
Provide instructions on how to use the application. For example:

Open your browser and navigate to http://localhost:5173.
Register for a new account or log in with an existing account.

#Here are few screenshots of my project:
![Screenshot_20240626_203724](https://github.com/samieruashovo/MERN_Food_Delivery/assets/84716783/ef7848fe-9e17-4fcf-8fd5-02c290a3f934)
![Screenshot_20240626_203747](https://github.com/samieruashovo/MERN_Food_Delivery/assets/84716783/c1bde32b-024c-4396-adc9-d56908cd2953)
![Screenshot_20240626_203832](https://github.com/samieruashovo/MERN_Food_Delivery/assets/84716783/80499452-a838-4786-9a11-fe73de5763ed)
![Screenshot_20240626_203845](https://github.com/samieruashovo/MERN_Food_Delivery/assets/84716783/5e6316b3-972e-4fce-bae9-47ffe963e128)
![Screenshot_20240626_203929](https://github.com/samieruashovo/MERN_Food_Delivery/assets/84716783/54ea917a-2e34-4e8b-8b6d-77338dece343)
![Screenshot_20240626_203908](https://github.com/samieruashovo/MERN_Food_Delivery/assets/84716783/94de8659-f2a1-426d-aae0-0676f73d154d)
