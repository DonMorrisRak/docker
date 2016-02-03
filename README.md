My Docker containers

Nginx:
docker build -t don-nginx .
docker run --name n1 -d -p 80:80 don-nginx
