# Wanderlust - Hotel Booking Application

Wanderlust is a web application that allows users to explore, book, and manage hotel stays. It provides a user-friendly interface for browsing through a wide range of accommodationsand performing CRUD (C reate, Read, Update, Delete) operations on stay listings.

## Features

- **Stay Listings**: Users can view a comprehensive list of available hotel stays, including details such as title, description, price, location, and country.
- **User Authentication**: Secure user registration and login system to personalize the booking experience and manage user-specific reservations.
- **Reviews and Ratings**: Integration of a review system allows users to provide feedback and ratings for the stays they have experienced, helping other users make informed decisions.
- **Responsive Design**: The application is built with a responsive layout, ensuring a seamless user experience across various devices and screen sizes.

## Technologies Used

- **Front-end**: HTML, CSS, JavaScript, EJS (Embedded JavaScript) templating engine
- **Back-end**: Node.js, Express.js
- **Database**: MongoDB with Mongoose as the ODM (Object Document Mapper)
- **Authentication**: Passport.js for user authentication and authorization
- **Session Management**: Express-session for handling user sessions
- **Error Handling**: Custom error handling middleware to provide informative error messages
- **Styling**: Bootstrap for responsive and visually appealing UI components

## Installation and Setup

1. Clone the repository: `git clone https://github.com/your-username/wanderlust.git`
2. Navigate to the project directory: `cd wanderlust`
3. Install the dependencies: `npm install`
4. Set up the MongoDB database and obtain the connection URL
5. Create a `.env` file in the root directory and add the necessary environment variables (e.g., database connection URL, session secret)
6. Start the application: `npm start`
7. Access the application in your browser at `http://localhost:8080/listings`