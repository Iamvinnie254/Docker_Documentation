# Service Orchestration - Docker

- Docker is an OS-level virtualization or containerization platform, which allows applications to share the host OS kernel instead of running a separate guest OS like traditional virtualization.
- This is a way of packaging software so that it can run on any hardware
  
  > Docker solves the problem of "It works on my machine" by ensuring code runs identically across environments

## Terms used/Key components

1. Docker Engine
2. Docker Image
3. Docker Container
4. Docker Engine Daemon (dockerd)
5. Docker Client (Docker CLI)
6. Dockerfile
7. Architecture of Docker
8. Docker REST API
9. Docker Hub/Registry
10. Docker Commands

## 1. Docker Engine

- Docker engine is an open source technology that includes a server running a background process called a REST API and a command-line interface (CLI) known as 'docker'.
- The Docker Engine is the actual technology behind building, shipping, and running container applications.
- It does its work in a client-server model, which requires using many components and services for such operations.
- Its main components are: Docker daemon, Docker Client, REST API

### Docker Engine Architecture

- *Docker Daemon* - Also called 'dockerd', is essential. It manages and runs Docker containers, handling their creation. It acts as a server in Docker's setup, receiving requests and commands from other components.
- *Docker client* - Users communicate with Docker through the CLI client (docker). This client communicates with the Docker daemon using Docker APIs, enabling direct command-line interaction or scripting. This flexibility enables diverse operational approaches.
- *Docker images and containers* - Images act as unchanging blueprints. Containers are created from these blueprints. Containers provide­ the surroundings needed to run apps.
- *Docker registries* - These are places where Docker images live and get shared.
- *Networking and volumes* - Docker has networking capabilities. They control how containers talk to one another and the host system. Volumes in Docker allow data storage across containers. This enhances data handling within Docker.

## Docker Image
