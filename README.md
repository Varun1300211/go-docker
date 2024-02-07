# Simple Golang HTTP Server Dockerized

This is a basic Golang HTTP server application containerized using Docker. It responds with "Hello, [URL Path]" for any route accessed and "Hello Docker!" for the "/docker" route.

## Requirements
- Docker installed on your system

## Quick Start
1. Clone this repository:
    ```bash
    git clone https://github.com/Varun1300211/go-docker.git
    ```

2. Navigate into the project directory:
    ```bash
    cd your-repository
    ```

3. Build the Docker image:
    ```bash
    docker build -t my-golang-server .
    ```

4. Run the Docker container:
    ```bash
    docker run -p 8081:8081 -it my-golang-server
    ```

5. Access the server in your browser or using cURL:
    - To access the root route:
        ```bash
        curl http://localhost:8081/
        ```
    - To access the "/docker" route:
        ```bash
        curl http://localhost:8081/docker
        ```

## Project Structure
- `main.go`: Contains the source code for the Golang HTTP server.
- `Dockerfile`: Specifies the Docker image configuration.
  

