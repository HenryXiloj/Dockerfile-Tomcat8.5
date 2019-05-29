# Dockerfile-Tomcat8.5

Basic Docker image to run Apache Tomcat.

Usage

Example:

docker build -t name_image .

docker image ls

docker run -p 8888:8080 -it -d --name container_name name_image 

go to browser

http://localhost:8888/

user: admin
pass: hxi123

