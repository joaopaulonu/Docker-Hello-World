### 🐳 Docker: Hello World Implementation

![Language](https://img.shields.io/badge/Tools-Docker-blue)
![Category](https://img.shields.io/badge/Category-Infrastructure-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Concept](https://img.shields.io/badge/Concept-Containerization-lightgrey)

---

## 🌟 Overview

This repository documents my first contact with **Docker**, the industry-standard tool for containerization. The goal of this project was to validate my local environment setup by executing the classic `hello-world` container.

This exercise marks the beginning of my journey into understanding how applications can be packaged with all their dependencies to run reliably in any environment.

---

## 🧩 The Challenge

The objective was to successfully interact with the Docker Daemon and run a container, confirming that the client-server architecture is correctly configured on my machine.

### What is "Hello World" in Docker?
It is a simple diagnostic image provided by Docker Hub that demonstrates the entire container lifecycle:
1. **Pulling**: Fetching the image from the registry.
2. **Creation**: Initializing a container based on that image.
3. **Execution**: Running the internal command to output the greeting.
4. **Communication**: Streaming the result back to the user's terminal.

---

## 📌 Execution Log (Validation)

The following output confirms that the Docker daemon is correctly communicating with the client and that the system is ready for development:

```text
C:\\Users\\jpnun> docker run hello-world
Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
4f55086f7dd0: Pull complete
Digest: sha256:96498ffd522e70807ab6384a5c0485a79b9c7c08ca79ba08623edcad154e62d
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.
...
