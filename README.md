# FastAPI Microservices Demo

This repository contains a FastAPI-based microservices setup using Docker Compose. It supports full CRUD operations.

## Prerequisites

Ensure you have the following installed on your system:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

Follow these steps to run the application:

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Start the services using Docker Compose:
   ```sh
   docker-compose up -d
   ```

3. Open the following URLs in your browser to test the API:
   - [Movies API Docs](http://localhost:8080/api/v1/movies/docs#/movies)
   - [Casts API Docs](http://localhost:8080/api/v1/casts/docs#/casts)

## Available Endpoints

### Movies API
- `GET /` – Get all movies in the database.
- `GET /{id}` – Get specific movie in the database.
- `POST /` – Add a new movie to the database.
- `PUT /{id}` – Update an existing movie by ID.
- `DELETE /{id}` – Delete a movie by ID.
- `GET /count` – Get the total count of movies in the database.

## Stopping the Services

To stop and remove the running containers, execute:
```sh
docker-compose down
```

## License
This project is licensed under the MIT License.

