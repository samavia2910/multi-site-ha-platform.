# Multi-Site Hosting Using Docker with Load Balancer

## Project Introduction
This project demonstrates hosting multiple websites using Docker containers and a load balancer.

## Objectives
- Host multiple websites using Docker.
- Run separate website containers.
- Configure a load balancer.
- Distribute incoming requests between websites.
- Understand containerization and networking.

## Technologies Used
- Ubuntu Linux
- Docker
- Docker Compose
- Nginx
- Git and GitHub

## Project Structure
- site-a: First website
- site-b: Second website
- load-balancer: Handles incoming requests
- docker-compose.yaml: Manages Docker services

## Working
Two websites run in separate Docker containers. Nginx acts as a load balancer and distributes incoming requests between the websites.

## How to Run

1. Install Docker.
2. Open the project directory.
3. Run:

   docker compose up -d

4. Open your browser and visit:

   http://localhost:8080

## Conclusion
This project demonstrates multi-site hosting, Docker containerization, and load balancing using Nginx.
