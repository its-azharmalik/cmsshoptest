# CMS Shop Test - Full-Stack MERN E-Commerce Platform

CMS Shop Test is a feature-rich e-commerce platform built using the MERN (MongoDB, Express, React, Node.js) stack. The project includes a user-friendly UI, admin panel for efficient management, payment gateway integration, and cloud deployment.

![CMS Shop Test](/path/to/screenshot.png)

## Features

- User-friendly shopping experience with React, Redux, and Bootstrap UI.
- Admin panel for streamlined management of orders, products, users, and deliveries.
- Seamless cart functionality with PayPal payment gateway and wallet support.
- Deployed on AWS EC2 using Docker for scalability and reliability.
- Efficient operations through pm2 process manager.
- End-to-end security with JWT authentication.

## Installation

1. Clone the repository:
   
git clone https://github.com/its-azharmalik/cmsshoptest.git

>Redux is used for State Management in this application.

Deployed and tested on Heroku & deployment on AWS and Azure as well.

2. Navigate to the project directory:

cd cmsshoptest

3. Install backend and frontend dependencies:
   
cd backend && npm install
cd ../frontend && npm install

4. Start the development server:
   
cd ../backend && npm start
cd ../frontend && npm start



5. Access the application at `http://localhost:3000` in your browser.

## Project Structure

- `backend`: Express server, API routes, authentication, and database models.
- `frontend`: React application, Redux store, UI components, and user interfaces.

## Technologies Used

- React
- Redux
- Express
- Node.js
- MongoDB
- Bootstrap
- JWT Authentication
- PayPal Payment Gateway
- Docker
- AWS EC2

## Deployment

- Deployed on AWS EC2 using Docker for scalability.
- Domain mapped with Route 53 DNS for easy access.

## Contributions

Contributions and improvements are welcome! Please feel free to submit pull requests or issues.

## License

This project is licensed under the [MIT License](LICENSE).

