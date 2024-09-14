To run a Docker container, you need to have Docker installed on your system. Here’s a step-by-step guide:

### 1. **Install Docker** 
   - If you don't already have Docker installed, you can download and install it from the [official Docker website](https://www.docker.com/get-started).

### 2. **Pull a Docker Ubuntu Image**
   - First, you need a Docker image to create a container. You can pull an image from Docker Hub using the `docker pull` command. For example, to pull the latest Ubuntu image:
     ```bash
     docker pull ubuntu
     ```

### 3. **Run a Docker Container**
   - Use the `docker run` command to start a new container. Here's a basic example:
     ```bash
     docker run ubuntu
     ```
   - This command runs the Ubuntu container. If you want to run a command inside the container, you can specify it like this:
     ```bash
     docker run ubuntu echo "Hello, Docker!"
     ```

### 4. **Run a Docker Container Interactively**
   - If you want to interact with the container's shell, use the `-it` options:
     ```bash
     docker run -it ubuntu
     ```
   - This opens an interactive terminal session in the Ubuntu container.

### 5. **Run a Docker Container in Detached Mode**
   - If you want to run a container in the background, use the `-d` option:
     ```bash
     docker run -ti --rm ubuntu /bin/bash
     ```
   - This runs the container in detached mode and returns the container ID.

### 6. **List Running Containers**
   - To see a list of running containers, use:
     ```bash
     docker ps
     ```
   - To see all containers, including stopped ones, use:
     ```bash
     docker ps -a
     ```

### 7. **Stop a Running Container**
   - To stop a running container, use the `docker stop` command followed by the container ID or name:
     ```bash
     docker stop <container_id>
     ```

### 8. **Remove a Container**
   - To remove a stopped container, use the `docker rm` command:
     ```bash
     docker rm <container_id>
     ```

### Example: Running a Python Container
If you want to run a Python script inside a container, you can use the Python image:
```bash
docker run python:3.9 python -c "print('Hello from Python in Docker!')"
```

You can replace `ubuntu`, `python:3.9`, and other images with any image available on Docker Hub.