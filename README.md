# uptime-kuma-docker
To install Uptime Kuma on your Docker using the repository you provided, follow these steps:

## Clone the Repository:
Open a terminal and clone the repository to your local machine using the following command:

    git clone https://github.com/rozicdejan/uptime-kuma-docker.git
Navigate to the Project Directory:
Change your working directory to the cloned repository:

    cd uptime-kuma-docker
## Check Docker and Docker Compose:
Make sure you have Docker and Docker Compose installed on your system. You can check by running:

    docker --version
    docker-compose --version
## Build and Start the Container:
Run the following command to build and start the Docker container using the provided docker-compose.yml file:

    docker-compose up -d
The -d flag is used to run the containers in detached mode.

## Verify the Setup:
After the containers are up and running, you can verify that Uptime Kuma is accessible by navigating to http://localhost:3001 in your web browser. Replace localhost with your server's IP address if you're running this on a remote server.

## Check Container Status:
To ensure everything is running smoothly, you can check the status of the containers:

    docker-compose ps
### Complete Command Sequence
Here is the complete set of commands you will need to run in sequence:

    git clone https://github.com/rozicdejan/uptime-kuma-docker.git
    cd uptime-kuma-docker
    docker --version
    docker-compose --version
    docker-compose up -d
    docker-compose ps
Following these steps will get Uptime Kuma up and running on your Docker environment.





