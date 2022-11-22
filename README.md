# Simple-Docker-Web-Server
A basic Node JS web server wrapped in a Docker Container
The following commands needs to be run inside the project directory to create a Docker container and start the web server

Step 1: Run docker build -t <image name> . or docker build . (this builds the docker image)
  
Step 2: Note the image ID or image name and run docker run -p 8080:8080 <image name / image ID> (Here, using both localhost and container port as 8080)
