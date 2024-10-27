

# Cross-Border Token Transfer System

A full-stack **Cross-Border Token Transfer System** that enables users to transfer digital tokens across international borders securely. This system leverages the MERN stack (MongoDB, Express, Node.js, React) alongside blockchain technology and fiat-to-token conversion, delivering a seamless experience for cross-border token transfers.

## Project Structure

The repository is organized as follows:

```
/backend
    ├── server.js                # Main server file
    ├── config/                  # Configuration files (e.g., database, env)
    ├── controllers/             # Controllers for various routes
    ├── models/                  # Database models
    ├── routes/                  # API routes
    └── utils/                   # Utility functions (e.g., auth, token handling)

/frontend
    ├── public/                  # Static files
    ├── src/                     
        ├── components/          # React components
        ├── pages/               # Page components for routes
        ├── services/            # API service calls
        └── App.js               # Main App component
```

## Key Features

- **User Authentication & Wallet Management**: Secure sign-up, login, and wallet creation.
- **Fiat-to-Token Conversion**: Convert fiat deposits into tokens in real time.
- **Token Transfers & Withdrawals**: Enables cross-border token transfers with blockchain security and supports fiat withdrawals.
- **Transaction History**: Tracks and displays all user transactions.
- **Admin Dashboard**: Allows admin monitoring of transactions, user activities, and report generation.

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB
- **Blockchain**: Stellar SDK/Web3.js
- **Authentication**: JWT, bcrypt

## Getting Started

### Prerequisites

Ensure you have Node.js and MongoDB installed on your machine.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies:**
   - Navigate to `/backend` and `/frontend` folders separately and run:
     ```bash
     npm install
     ```

3. **Environment Variables:**
   - In `/backend`, create a `.env` file for environment variables:
     ```
     MONGO_URI=<your-mongo-db-uri>
     JWT_SECRET=<your-jwt-secret>
     STELLAR_NETWORK=<stellar-network-url>
     ```
   - In `/frontend`, create a `.env` file with:
     ```
     REACT_APP_BACKEND_URL=<backend-api-url>
     ```

### Running the Application

- **Backend**:
  ```bash
  cd backend
  npm start
  ```

- **Frontend**:
  ```bash
  cd frontend
  npm start
  ```

- **Accessing the App**: Navigate to `http://localhost:3000` in your browser.

## Development Workflow

1. **Branching**: Each team member should create a branch for their task. Example:
   ```bash
   git checkout -b feature/authentication
   ```

2. **Code Commit & PR**: Commit code regularly, and submit pull requests for review before merging.

3. **Communication**: Use comments in your pull requests to provide context on code changes.

4. **Testing**: Test your features locally before creating a pull request. Regularly pull from the main branch to avoid conflicts.

## Deployment

Use platforms like Vercel, Render, or Heroku to deploy both the frontend and backend. Ensure environment variables are set up on the platform.

## Contributing

For any changes, please:

1. Open an issue describing the change or feature.
2. Assign yourself the task and create a feature branch.
3. Submit a pull request linking to the issue.

