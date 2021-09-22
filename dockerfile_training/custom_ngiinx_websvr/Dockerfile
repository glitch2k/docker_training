FROM nginx
# this gets a basic clean nginx image

WORKDIR /usr/share/nginx/html/
# this sets the current working directory to /usr/share/nginx/html

RUN rm index.html
# this runs a bash command to delete the file "index.html"

COPY ./index.html .
# this copys the file "index.html" from the current directory on the host from 
# where the "docker build" is executed

EXPOSE 80
# this will expose the port "80" when a container is built from this image
