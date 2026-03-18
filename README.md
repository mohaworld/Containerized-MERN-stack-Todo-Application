# Containerized MERN Stack Todo Application

This project demonstrates how to run a full MERN stack application using Docker and Docker Compose with Nginx as a reverse proxy.

<img width="1012" height="283" alt="image" src="https://github.com/user-attachments/assets/a1de170c-6ec5-48b2-a4dc-736f4f0670e4" />


## Tech Stack

- React (Frontend)
- Node.js + Express (Backend)
- MongoDB (Database)
- Nginx (Reverse Proxy)
- Docker
- Docker Compose

## Architecture
User → Nginx → React → Node API (/api) → MongoDB


                    
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

## Project Structure

Containerized-MERN-stack-Todo-Application
│
├── todoapp-backend
│   └── Backend application files
│
├── todoapp-frontend
│   └── Frontend application files
│
└── README.md

