# Full Stack Application with Docker 🐳

This repository contains a comprehensive example of a full stack application, complete with a Frontend, Backend, and Database, all orchestrated using Docker containers.

## Components

### 1. Frontend

- [Frontend Repo](https://github.com/nikcladis/DockerApp/tree/master/mern-docker/frontend)
- Technologies used:
    - React
    - React Router DOM

### 2. Backend

- [Backend Repo](https://github.com/nikcladis/DockerApp/tree/master/mern-docker/backend)
- Technologies used:
    - Node
    - Express

### 3. Database

- [Database Repo](https://github.com/nikcladis/DockerApp/tree/master/mern-docker/backend/database)
- Technologies used:
    - MongoDB
    - Mongoose

## Docker Setup

Each component (Frontend, Backend, and Database) is containerized using Docker. The Dockerfiles and docker-compose.yml files are included in their respective directories.

### Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/nikcladis/DockerApp.git
    cd mern-docker
    ```

2. Build and run the containers:

    ```bash
    sudo docker compose up --build
    ```

3. Access the application in your browser at [http://localhost:5173](http://localhost:5173/).


4. Watch live changes to your code:

   ```bash
   sudo docker compose watch
