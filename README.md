# Invite - MERN Stack (Event Management System)

This project is a full-stack web application built using React for the frontend and Express.js with MongoDB for the backend. The frontend features a register, login page, homepage which links to the events page that features all upcoming events. Events page also contains filtering functionality based on date and category of events. Each event leads to the event details page.

The event detail page that displays information such as title, location, photos, descritions, no of participants, host information, event status, etc. 

To use the application, users must first sign up with their name, email and password. Once signed in, they can browse through all events, register them, create new ones, edit them, etc. The profile page shows all events registed by them along with their user information. The application also provides a logout button to ensure the user's privacy and security.

TailwindCSS is used to style the web application. Full validation and error handling is done on both frontend and backend.
 
## Installation

To run this project, you'll need to have Node.js and MongoDB installed on your system. You can download Node.js from the official website: https://nodejs.org/, and install MongoDB by following the instructions provided here: https://docs.mongodb.com/manual/installation/.

To install the project dependencies, follow these steps:

Clone the repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-name/your-project-name.git
Navigate to the project directory:

bash
Copy code
```bash
cd your-project
```
Navigate and install the frontend dependencies:
```bash
cd client
npm install
```
Navigate and install the backend dependencies:
```bash
cd server
npm install
```

Create a .env file in the backend directory, and set the following environment variables:

makefile
```bash
MONGO_URI=<your-mongodb-uri>
PORT=<port>
JWT_SECRET=<your-jwt-secret>
```
Replace <your-mongodb-uri> with the URI of your MongoDB database.
Replace <port> with the URI of your port.
Replace <your-jwt-secret> with your jwt secret.

Start the backend server:

```bash
npm start
```
Open a new terminal window, navigate to the project directory, and start the frontend server:

```bash
npm start
```
Open your web browser and navigate to http://localhost:5173 to view the application.

That's it! You should now be able to run the application locally. If you encounter any issues, please refer to the project documentation or create a new issue on the project's GitHub repository.
    
  
