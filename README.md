# ToDo App using React JS and GoLang

## Overview
The Todo Web Application is designed to help users manage their daily tasks efficiently. It offers a seamless user experience with a robust backend and a modern, responsive frontend. The application is built using TypeScript for the frontend and Golang for the backend, ensuring a strong type system and high performance.
## Features

**User Authentication**

- Secure user login and registration using JWT.

**RESTful API**

- Provides endpoints for managing users and tasks.

**Database Operations**

- CRUD operations for user and task data with MongoDB.

**Error Handling**

- Comprehensive error handling for robust performance.

**Scalability**

- Designed to handle a large number of users and tasks efficiently.

## Dependencies

**Frontend**

- **TypeScript**:Frontend programming language.
- **React JS**:Fast and efficient web framework for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling.

**Backend**

- **Go**: Backend programming language.
- **Fiber**: Fast and efficient web framework for Go.
- **MongoDB**: NoSQL database for storing application data.
- **JWT (JSON Web Tokens)**: For secure authentication between services.

**Development Tools**

- **Git**: Version control system.
- **VS Code**: Integrated development environment (IDE) for coding.
- **Postman**: API testing tool.

## Development Workflow
1. **Frontend**:
   - Use `Vite` for a fast development server and efficient build process.
   - Write components in TypeScript for better type safety and IntelliSense.
   - Style components using Tailwind CSS for a utility-first approach.

2. **Backend**:
   - Set up the `Fiber` framework for handling HTTP requests.
   - Implement `JWT` authentication for secure access control.
   - Connect to a `MongoDB` database for storing user and task data.
   - Develop RESTful API endpoints for all CRUD operations.


### Prerequisites
- Node.js
- Golang
- MongoDB

## Installation

 Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-web-app.git
   cd todo-web-app
   ```

 Install frontend dependencies:
   ```bash
   cd frontend
npm install
   ```

 Install backend dependencies:
   ```bash
go mod tidy
   ```

## Run Locally

Start the server

```bash
  go run main.go
```

Run the application

```bash
  cd frontend
  npm run dev
```

## Contributing

Contributions are always welcome!Please fork the repository and submit a pull request.
