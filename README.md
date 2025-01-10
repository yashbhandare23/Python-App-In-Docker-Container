# Python-App-In-Docker-Container

This repository provides a step-by-step guide to building and running a Python application in a Docker container. It includes all necessary files and commands for creating a Docker image, configuring the container, and executing the Python app.

Folder Structure:
Build-and-Run-Python-App-In-Docker/
├── python-image/
│   ├── app.py          # Python script for demonstration
│   ├── Dockerfile      # Dockerfile with instructions
├── README.md           # Detailed project documentation

Dockerfile Explanation:
- FROM: Specifies the base image (e.g., python).
- WORKDIR: Sets the working directory inside the container.
- COPY: Copies files from the host to the container.
- CMD: Defines the default command to run (python3 app.py).
![Screenshot 2025-01-10 095448](https://github.com/user-attachments/assets/b22b03ba-1d48-4495-8a1f-13b29ad6e876)
![Screenshot 2025-01-10 095503](https://github.com/user-attachments/assets/9786c913-eb97-4e47-bd4a-b1888540446b)


Building Docker Images:
- Build the image with docker build -t <image-name> ..
- Tag the image for easy identification.
![Screenshot 2025-01-10 095535](https://github.com/user-attachments/assets/5c0289ce-006b-4fdc-a633-2aa8c32e17a4)

Running Docker Containers:
- Run the container using docker run <image-name>.
- Specify container names with --name for better management.
![Screenshot 2025-01-10 100459](https://github.com/user-attachments/assets/ab9f1cd6-5e18-469a-9e92-5b8c8978ecc0)

Managing Files and Directories:
- Demonstrates listing files and directories within the container.
- Copies and runs scripts dynamically.
![Screenshot 2025-01-10 100528](https://github.com/user-attachments/assets/26d4a9ae-f498-4cf3-9008-c921ed736618)
![Screenshot 2025-01-10 101326](https://github.com/user-attachments/assets/e8e36092-bac8-483e-b4aa-0207cb907229)

This repository is ideal for beginners to understand the basics of Docker and how to containerize Python applications.
