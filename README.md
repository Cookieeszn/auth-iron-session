# Full-Stack Website

A web application built with React for the front-end and Node.js for the back-end, featuring user authentication with the `iron-session` package.

## Project Overview

This full-stack website combines React on the client side with a Node.js server. The application features a secure authentication system powered by the `iron-session` npm package, allowing users to sign up, log in, and access protected content based on their session state.

## Features

- **Frontend:** Built with React, offering a responsive and user-friendly interface.
- **Backend:** Powered by Node.js and Express, managing API routes and business logic.
- **Authentication:** Secure session-based authentication using the `iron-session` package.
- **Protected Routes:** Access to certain pages and features is restricted to authenticated users.

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (vX.X.X or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repository
    ```

3. Install dependencies for both the client and server:

    ```bash
    # Install client dependencies
    cd client
    npm install

    # Install server dependencies
    cd ../server
    npm install
    ```

### Running the Application

1. Start the server:

    ```bash
    cd server
    npm run dev
    ```

2. Start the client:

    ```bash
    cd ../client
    npm start
    ```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Environment Variables

Create a `.env` file in the `server` directory to store your environment variables (e.g., database URL, session secret, etc.). An example `.env` file might look like:

  ```bash
  SESSION_SECRET=your-session-secret
  MONGO_URI=your-mongodb-uri
  ```

### Learn More

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [iron-session Documentation](https://www.npmjs.com/package/iron-session)

### Contributing

Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

