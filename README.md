CI/CD Tools and Practices Final Project Template

## Features

- RESTful API for managing counters
- In-memory storage
- Comprehensive error handling
- Security middleware (Helmet, CORS)
- Logging middleware
- Full test coverage with Jest
- Docker support
- Health check endpoint

## API Endpoints

- `GET /` - Service information
- `GET /health` - Health check
- `GET /counters` - List all counters
- `POST /counters/:name` - Create a new counter
- `GET /counters/:name` - Read a specific counter
- `PUT /counters/:name` - Increment a counter
- `DELETE /counters/:name` - Delete a counter

## Setup

1. **Install dependencies:**
   ```bash
   npm install
