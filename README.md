# Containerized MERN Stack Todo Application

This project demonstrates how to run a full MERN stack application using Docker and Docker Compose with Nginx as a reverse proxy.

## Tech Stack

- React (Frontend)
- Node.js + Express (Backend)
- MongoDB (Database)
- Nginx (Reverse Proxy)
- Docker
- Docker Compose

## Architecture

User
  |
  v
Nginx
  |
  |------> React Frontend
  |
  |------> Node.js API (/api)
              |
              v
           MongoDB

## Run the Project

Clone the repository:

```bash
git clone https://github.com/mohaworld/Containerized-MERN-stack-Todo-Application.git

Navigate to the project:
cd Containerized-MERN-stack-Todo-Application

Start the containers:
docker compose up --build

Open your browser and visit:
http://localhost

