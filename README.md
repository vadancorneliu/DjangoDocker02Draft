# Dockerized Django Server

This project provides a Dockerized environment for running a Django server. By downloading the files onto your local machine and performing the specific steps in Docker Desktop (for Dev Environment), a Docker container will be created and initialized with the Django server. You can then modify the Django script using Visual Studio Code on your local machine.

## Table of Contents

1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Files](#files)
5. [License](#license)

## Requirements

Make sure you have installed all of the following prerequisites on your development machine:
- Visual Code Studio (https://code.visualstudio.com/);
- Visual Studio Code Remote Containers Extension (https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- Docker Desktop (https://www.docker.com/products/docker-desktop/);
- Git (https://git-scm.com/).


## Installation

To get started with this project, follow these steps:

1. Open Command Prompt and navigate to the your install directory:

```
cmd
```

```
cd YourDirectory
```

2. Clone the repository to your local machine:

```
git clone https://github.com/vadancorneliu/DjangoDocker02Draft.git
```

3. Performing the specific steps in Docker Desktop 
Launch the Docker Desktop application on your Windows system.
In the Docker Desktop interface, navigate to the "Dev Environments" section, click on the "Create a new environment" button and follow these steps:
Step 1 – Overview – Create a Dev Environment
- click on the "Get Started" button
Step 2 – Setup – Create a Dev Environment
- input dev environment name in the text field with label "Name"
- select "Local directory" option and click on the "Select" button
- select the project folder and click on the "Select Folder" button
- click on the "Continue" button
Step 3 – Preparing – Create a Dev Environment
- click on the "Continue" button
Step 4 – Ready – Create a Dev Environment
- click on the "Done" button



## Usage

- Once the container is up and running, you can access the Django server locally at [http://localhost:8000](http://localhost:8000).
   
- You can then modify the Django script using Visual Studio Code on your local machine, in the following way:
  In the Docker Desktop interface, navigate to the "Dev Environments" section, select the appropriate container and click the "OPEN IN VSCODE" button.
  Visual Code Studio is launching and follow these steps: 
	- once the windows with the message ”Workspace does not exist” is open, click the ”Open Workspace...” button
	- select the project folder and click on the "OK button
  Now, Visual Code Studio is open and in Explorer section we have project files. 


## Files

This repository contains the following files:

- `Dockerfile`: Dockerfile for building the Docker image.
- `compose-dev.yaml`: Docker Compose file for defining services.
- `requirements.txt`: List of Python dependencies.
- `README.docx`: Description of the project.


## License

This project is licensed under the [Unlicense](UNLICENSE.txt).
