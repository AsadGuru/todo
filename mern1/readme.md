Installation

1: Run the command to clone the repository

2: Go to frontend and backend directory to install packages

3: Configurations: Create .env file inside backend directory and copy the following code -:


**MONGO_URI=Your mongodb URI
GMAIL_USERNAME=your gmail address 
GMAIL_PASSWORD=password created inside 'App Password' section under google accounts setting
PORT=8000
JWT_SECRET=a random secret key eg. thisisasecretkey**

4: Run the application
Go to backend and frontend directory and start the server

cd backend
nodemon server

cd frontend
npm start

