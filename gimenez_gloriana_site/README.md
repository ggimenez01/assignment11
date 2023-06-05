# Gimenez_Gloriana_Coding_Assignment11

This repository contains a web application built using Create React App.
## To Create A new React Project
1. Open a terminal or command prompt.
2. Navigate to the directory where you want to create the project.
3. Run the following command to create a new React app:
    npx create-react-app gimenez_gloriana_coding_assignment11
4. Navigate to the project directory:
    cd gimenez_gloriana_coding_assignment11
5. type npm start.

## Running the Application

To run the web application on your local machine, follow these steps:

1. Install Docker Desktop(https://www.docker.com/get-started/0) on your system if you haven't already.

2. Clone the repository using GitHub Desktop URL (https://github.com/ggimenez01/dockers_assignment11.git) to your local machine.

3. Once downloaded, open a terminal or command prompt and navigate to the to the clone repository for example, type cd C:\dockers_assignment11\gimenez_gloriana_site
4. To run in the docker container, build the Docker Image by typing this:
    docker build -t gimenez_gloriana_coding_assignment11 .

5. Then run the docker container, by typing this:
    docker run -p 7775:3000 gimenez_gloriana_coding_assignment11

This will start the container and map port 7775 of your local machine to port 3000 inside the container.

6. Open your web browser and navigate to http://localhost:7775/ to view the website running in the Docker container.

If encounter an issue.
1. Open your terminal and navigate to your repository directory
2. Type npm install 
3. Type npm start
