# BookShelf-Project
# BookShelf - Personal Book Tracker

A full-stack application for tracking and managing your personal book collection. Built with Spring Boot and React.

## Features

- Add, edit, and delete books
- Categorize books by reading status (Read, Unread, In-progress)
- Filter books based on reading status
- User-friendly interface
- RESTful API architecture
- Cloud-hosted on Azure

## Tech Stack

- Backend:
  - Java
  - Spring Boot
  - MySQL
  - REST API
- Frontend:
  - React
  - Material-UI
- DevOps:
  - Git
  - Azure App Services
  - Azure Repos

## Project Structure

```
bookshelf/
├── backend/           # Spring Boot application
│   ├── src/
│   └── pom.xml
└── frontend/         # React application
    ├── src/
    └── package.json
```

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Build the project:
   ```bash
   ./mvnw clean install
   ```

3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## API Documentation

The backend API will be available at `http://localhost:8080/api/v1`

### Endpoints

- GET /api/v1/books - Get all books
- GET /api/v1/books/{id} - Get book by ID
- POST /api/v1/books - Create new book
- PUT /api/v1/books/{id} - Update book
- DELETE /api/v1/books/{id} - Delete book

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
