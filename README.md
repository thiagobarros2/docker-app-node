####


docker build -t app-node:1.0 .
docker run -d -p 8080:3000 app-node:1.0 