# User Authentication System with Node.js

This project offers authentication services for users, including Signup/Register and Login/Logout APIs. It prioritizes security by implementing various layers of authorization and authentication. Unlike other authentication libraries like Passport or JWT, this project constructs APIs from scratch, ensuring security at each level. Token-based authentication is employed, utilizing custom-made expirable tokens instead of JWT, encrypted and decrypted via crypto using a secret key.

## Technologies Used

- **Node.js**: Platform for building the backend server.
- **Express.js**: Web application framework for Node.js, used for routing and handling HTTP requests.
- **MongoDB**: Database system used for storing user data.
- **Crypto**: Module for encryption and decryption, used for securing tokens.

## Features

- **Signup/Register API**: Allows users to create new accounts.
- **Login/Logout API**: Provides authentication for users to log in and log out securely.
- **Custom Token Authentication**: Uses custom-made expirable tokens for authentication.
- **Security**: Prioritizes security by implementing various layers of authorization and authentication.
- **No External Libraries**: APIs are constructed from scratch without relying on external authentication libraries or OAuth services.

## Getting Started

To run the project locally, follow these steps:

1. Install Node.js and MongoDB on your system if not already installed.
2. Clone this repository.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up MongoDB and configure the database connection in the project.
5. Start the server:
   ```bash
   npm start
   ```

## Usage

Use the provided APIs for signup/register and login/logout functionalities to authenticate users securely.
