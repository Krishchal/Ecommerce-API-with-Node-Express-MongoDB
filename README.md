# Backend E-Commerce Project

## Project Overview

**Name:** backend-ecom  
**Version:** 1.0.0  

This project is a backend application for an e-commerce platform. 
It provides APIs for user authentication, product management, and order processing, among other features.

## Features

- User authentication and authorization using JSON Web Tokens (JWT).
- Secure password storage with bcrypt.js.
- Cross-Origin Resource Sharing (CORS) enabled.
- Environment variable management with dotenv.
- Database interaction using Mongoose with MongoDB.

## Project Structure

```
Backend ecom
├── .git
├── .gitignore
├── app.js
├── package-lock.json
├── package.json
└── src
    ├── [additional source code files]
```

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd Backend ecom
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

### Running the Application

Start the application in development mode:
```bash
npm start
```

The default entry point is `app.js`. Ensure that all required environment variables are defined in a `.env` file.

### Environment Variables

Create a `.env` file in the root of the project and configure the following variables:
```
PORT=5000
DB_URI=<your_mongo_db_connection_string>
JWT_SECRET=<your_jwt_secret_key>
```

## Dependencies

The project uses the following dependencies:

- **bcryptjs**: `^2.4.3` - Password hashing
- **cookie-parser**: `^1.4.7` - Cookie handling
- **cors**: `^2.8.5` - Enable CORS
- **dotenv**: `^16.4.5` - Manage environment variables
- **express**: `^4.21.1` - Web framework
- **jsonwebtoken**: `^9.0.2` - Token-based authentication
- **mongoose**: `^8.8.1` - MongoDB object modeling
- **nodemon**: `^3.1.7` - Development server

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
Krishchalregmi@gmail.com
For any inquiries, please contact the project maintainer.
