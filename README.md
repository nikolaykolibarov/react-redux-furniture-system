# React Redux Furniture System

A furniture management system built with React and Redux, allowing users to browse, create, edit, and manage furniture items with user authentication.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React |
| State Management | Redux, Redux Thunk, Redux Form |
| Routing | React Router |
| UI Components | Material-UI |
| HTTP Client | Axios |
| Build Tool | Webpack |
| Backend | Express.js |
| Authentication | Passport.js, JWT |

## Features

- User authentication (register, login, logout)
- Browse furniture catalog
- Create new furniture items
- Edit and delete furniture (owner only)
- View furniture details
- User account management
- Persistent state with Redux Persist

## Prerequisites

- Node.js (v8+)
- npm

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nikolaykolibarov/react-redux-furniture-system.git
   cd react-redux-furniture-system
   ```

2. Install server dependencies:
   ```bash
   cd server
   npm install
   ```

3. Install client dependencies:
   ```bash
   cd ../client
   npm install
   ```

## How to Run

1. Start the server:
   ```bash
   cd server
   npm start
   ```

2. In a new terminal, start the client:
   ```bash
   cd client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:8080`

## Project Structure

```
react-redux-furniture-system/
├── client/
│   ├── src/
│   │   ├── account/         # User account components
│   │   ├── authentication/  # Auth components (login, register)
│   │   ├── furniture/       # Furniture CRUD components
│   │   ├── layouts/         # Layout components
│   │   ├── shared/          # Shared utilities and components
│   │   ├── store/           # Redux store configuration
│   │   ├── App.js           # Main app component
│   │   └── Routes.js        # Route definitions
│   ├── index.html
│   └── webpack.config.js
└── server/
    ├── data/                # Data storage
    ├── middleware/          # Express middleware
    ├── passport/            # Passport configuration
    ├── routes/              # API routes
    └── index.js             # Server entry point
```

> **Note:** This project was created as an exam solution for the ReactJS Fundamentals course at Software University (SoftUni).
