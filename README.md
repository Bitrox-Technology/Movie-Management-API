# Movie Management API

A RESTful API built with Go that manages a collection of movies. This project uses the `mux` router for handling HTTP requests.

---

## Features

- **GET** `/movies`: Retrieve all movies.
- **GET** `/movies/{id}`: Retrieve a specific movie by ID.
- **POST** `/movies`: Add a new movie.
- **PUT** `/movies/{id}`: Update an existing movie.
- **DELETE** `/movies/{id}`: Delete a movie by ID.

---

## Prerequisites

- Go (version 1.18 or higher)
- Basic understanding of RESTful APIs

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Bitrox-Technology/Movie-Management-API.git
cd movie-management-api

The project uses the mux router. Install it using:
go get -u github.com/gorilla/mux

go run main.go
