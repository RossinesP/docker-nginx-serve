# docker-nginx-serve

A simple docker image to run a production build of a VueJS project

# Build 
docker build -t nginx-serve .

# Run (from any folder, to serve that folder)
docker run -p 80:80 -v $(pwd):/usr/share/nginx/html nginx-serve
