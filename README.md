# CodeAlpha Docker Web Server

## Objective
Deploy a web server using Docker.

## Technologies Used
- Docker
- Nginx
- HTML

## Commands Used

docker build -t my-webserver .

docker run -d -p 8080:80 --name webserver my-webserver

## Output

The web server runs successfully on:

http://localhost:8080
