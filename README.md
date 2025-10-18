# Movie Booking System

## Overview
This project is a movie booking system that allows users to browse theatres, movies, and shows, and book seats for their favorite movies. Built using Node.js, Express, and MongoDB with Mongoose ODM, the API handles user authentication, movie and theatre management, show scheduling, and booking functionalities.

## Features
- User registration, authentication, and authorization using middleware  
- CRUD operations on movies, theatres, and showtimes  
- Real-time seat booking and availability tracking  
- Structured data management with Mongoose models  
- RESTful API routes following best practices  
- JSON responses with error handling  

## Folder Structure & Key Files

- `server.js`: Entry point of the app, sets up Express server and middleware  
- `authMiddleware.js`: Middleware to secure routes and authorize users  
- **Models** (Mongoose schemas for MongoDB)  
  - `userModel.js`: Defines user schema with authentication details  
  - `movieModel.js`: Defines movie schema with details like title, language  
  - `theatreModel.js`: Schema for theatres with location and seating  
  - `showModel.js`: Defines movie screening times tied to theatres  
  - `bookingModel.js`: Manages booking records and status  
- **Routes** (Express route handlers)  
  - `usersRoute.js`: Handles user sign-up, login, profile  
  - `moviesRoute.js`: API endpoints for movie data management  
  - `theatresRoute.js`: Theatre related routes for adding, updating, retrieving theatres  
  - `bookingsRoute.js`: Booking operations including seat selection and confirmation  

## Technologies Used
- Node.js and Express.js for server-side development  
- MongoDB as the database with Mongoose as ODM  
- JSON Web Tokens (JWT) for user authentication  
- REST API design principles  
- JavaScript for backend logic  

## Getting Started

1. Clone the repository  
2. Run `npm install` to install dependencies  
3. Set up `.env` with MongoDB URI and JWT secret  
4. Run `node server.js` or `npm start` to start the server  
5. Use tools like Postman to test endpoints  

## Future Enhancements
- Add payment gateway integration for bookings  
- Implement real-time notifications for booking status  
- Frontend integration with React/Vue.js for user-friendly interfaces  
- Analytics dashboard for theatres and movie management  

## Contact
For questions or collaboration, contact Prashant Kushwaha at pacific24k@gmail.com.
