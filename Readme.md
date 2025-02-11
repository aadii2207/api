IRCTC API
This project is a simple IRCTC API built using Node.js, Express, and MySQL. It allows users to book train tickets, manage their bookings, and access other railway-related data through API endpoints.

Features
User Authentication: Users need to log in to book tickets and view their bookings.

Admin Security: Admin API endpoints are protected with an API key, ensuring only authorized users can add or modify data.

Secure Booking System: To book a seat or view a booking, users must provide an Authorization Token received after login.


Setup and Installation
Prerequisites


Node.js
MySQL

Steps to Run the Project
Clone the repository using git clone 

cd irctc (folder name is irctc)
Install dependencies using 

npm install


Create a .env file in the root folder and add the following details:

PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword (mysql workbench password )
DB_NAME=irctc_db   (it can be different according to programmer)
JWT_SECRET=your_jwt_secret 
API_KEY=your_api_key


Start the server:

npm start
The server will run at http://localhost:3000.
Testing (Optional)
I use Postman to test the API endpoints;
