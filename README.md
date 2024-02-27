# C01Lab6
## Table of Content
- [Objective](#objective)
- [Docker Image](#docker-image)
- [Instruction](#instruction)
- [GitHub Action](#github-action)
### Objective
- Understanding the process of containerizing Node.js applications with Docker
- Learning how to create Docker images and run Docker containers for Node.js applications
- Configuring a CI/CD pipeline with GitHub Actions
### Docker Image
- Quirk note backend image is published on [felixlyy/quirknotes_backend](https://hub.docker.com/repository/docker/felixlyy/quirknotes_backend/general)
- Quirk note frontend image is published on [felixlyy/quirknotes_frontend](https://hub.docker.com/repository/docker/felixlyy/quirknotes_frontend/general)
### Instruction
- Clone this repo
- On root, run 
    ```
    docker-compose up
    ```
    - This will automatically run both frontend and backend with latest image 
- Open browser and navigate to `localhost:3000` and enjoy the quirknote taking
### GitHub Action
- Latest [frontend](https://hub.docker.com/repository/docker/felixlyy/quirknotes_frontend/general) and [backend](https://hub.docker.com/repository/docker/felixlyy/quirknotes_backend/general) image is pushed to docker hub whenever we push to `main` branch