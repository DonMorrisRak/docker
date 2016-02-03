My Docker containers

Nginx:
docker build -t don-nginx .
docker run --name n1 -d -p 80:80 don-nginx

Workflow - change content in the git directory and PUSH -> PULL to new servers and build Docker.  
