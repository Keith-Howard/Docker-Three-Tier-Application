# Docker Three Tier Application

This is a 3-tier application with docker containers for the client, server
and datastore. The Client is React, the server is Node/Express and the 
Datastore is MongoDB. Faker is used to create generic data for creating users.

# Installation

To run this program Make sure you have Node.JS and Docker Hub installed on your 
computer. Download the files from the repository. In order to run this you need 
to have a local web server. How to install local, In VS Code open project folder 
where all files have been unzipped In Terminal window execute npm install in the 
client directory and in the server directory. Execute node index.js in the server 
directory and in another terminal run npm start in the client directory. You must 
create a Docker image as well by executing in both client and server directorys 
docker-compose up. This will create Docker Images in Docker Hub.
