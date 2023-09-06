# E-Commerce Website using MERN Stack

This is a full-stack e-commerce website built using the MERN (MongoDB, Express, React, Node.js) stack. It provides a platform for users to browse and purchase products online.

## Features

- User authentication and authorization.
- Product catalog with search and filtering options.
- Shopping cart functionality.
- Secure payment processing.
- User profile management.
- Order history tracking.
- Admin panel for product management.
- and more...

## Technologies Used

- **Frontend**: React, Redux, React Router, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Gateway**: Stripe
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Heroku, Netlify

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB database (you can set up a local instance or use a cloud-based service like MongoDB Atlas).
- Stripe API key (for payment processing).

### Installation

1. Clone the repository:

   ```bash
(https://github.com/vaishnavisk1212/Eshop-web)

Install server dependencies:

bash
Copy code
cd server
npm install
Install client dependencies:

bash
Copy code
cd ../client
npm install
Configure environment variables:

Create a .env file in the server directory and set up your environment variables (

e.g.
PORT = 
DB_URL =
JWT_SECRET_KEY = 
JWT_EXPIRES = 
ACTIVATION_SECRET = 
SMPT_SERVICE = 
SMPT_HOST = 
SMPT_PORT = 
SMPT_PASSWORD =
SMPT_MAIL = 
STRIPE_API_KEY =
STRIPE_SECRET_KEY = 

CLOUDINARY_NAME=
 CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=


).
Start the development server:

bash
Copy code
cd ../ frontend:
npm start
cd ../ backend:
npm start
cd ../ socket:
npm start


.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The MERN stack community for providing valuable resources and tutorials.
The creators of the libraries and tools used in this project.
