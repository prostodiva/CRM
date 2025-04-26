# CRM System

A Customer Relationship Management (CRM) system built with Spring Boot backend and HTML/CSS/JavaScript frontend.

## Project Structure

The project is divided into two main components:

### Frontend (`crmFront/`)
- Simple and intuitive web interface
- Built with HTML, CSS, and vanilla JavaScript
- Features:
  - Customer management interface
  - New customer registration
  - Responsive design

### Backend (`crmBackend/`)
- Built with Spring Boot
- RESTful API architecture
- Maven for dependency management
- Docker support for containerization

## Prerequisites

- Java 17 or higher
- Maven
- Docker (optional, for containerization)
- Web browser

## Getting Started

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd crmBackend
   ```

2. Build the project:
   ```bash
   ./mvnw clean install
   ```

3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

   The backend server will start on `http://localhost:8080`

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd crmFront
   ```

2. Open `index.html` in your web browser

   You can also use a local development server like Python's SimpleHTTPServer:
   ```bash
   python -m http.server 3000
   ```

   Then access the application at `http://localhost:3000`

## Docker Support

The application includes Docker support through `compose.yml`. To run the application using Docker:

```bash
docker-compose up
```

## Features

- Customer management
- Contact information tracking
- Simple and intuitive user interface
- RESTful API endpoints
- Secure data storage

## Development

- Backend is developed using Spring Boot with Maven for dependency management
- Frontend uses vanilla JavaScript for simplicity and ease of maintenance
- Docker support for containerized deployment

