frontend 
A frontend application built with React. This project includes a Sign Up page, a Log In page, and a Dashboard page. It demonstrates API integration, form validation, and responsive design.

Features
Sign Up: Users can register with their first name, email, password, and phone number.
Log In: Registered users can log in using their email and password.
Dashboard: Logged-in users can view their information on the dashboard.
Technologies Used
React: Front-end framework.
Axios: For making HTTP requests.
React Router: For routing.
Local Storage: For storing user information after login.
Installation
Clone the repository:


Install dependencies:

npm start
Start the development server:

npm start
Project Structure
src/
|-- components/
|   |-- SignUp.js
|   |-- Login.js
|   |-- Dashboard.js
|-- App.js
|-- index.js
Usage
Sign Up
Navigate to the Sign Up page at /signup.
Fill in the form with your first name, email, password, and phone number.
submit the form to register.
Usage
Sign Up

Navigate to the Sign Up page at /signup.
Fill in the form with your first name, email, password, and phone number.
Submit the form to register. Log In
Navigate to the Log In page at /login.
Enter your registered email and password.
Submit the form to log in. 4.Upon successful login, you will be redirected to the Dashboard.
Dashboard

After logging in, you will be redirected to the Dashboard at /dashboard.
The dashboard displays your user information.
API Endpoints
User Registration URL: https://syoft.dev/Api/user_registeration/api/user_registeration

Method: POST

Payload:

{
  "user_firstname": "mani",
  "user_email": "mail@gmail.com",
  "user_phone": "9876543210",
  "user_password": "123456",
  "user_lastname": "ni",
  "user_city": "Hyderabad",
  "user_zipcode": "500072"
}
User Login URL: https://syoft.dev/Api/userlogin/api/userlogin

Method: POST

Payload:

{
  "user_email": "mail@gmail.com",
  "user_password": "123456"
}