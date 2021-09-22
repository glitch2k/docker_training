# everthing dockerfile

## first lesson
* create an nginx image for web server with custom index page

## work notes
* default loction for for static content on the web server
  * /usr/share/nginx/html
* docker command to test the creation of an adhoc nginx container
  * docker run --name nginx-web-svr -v /some/content:/usr/share/nginx/html -d nginx
* docker command to create nginx svr with bind mount pointing to a transfer folder on container
  * docker run --name nginx-web-svr -v /working/folder:/transfer_folder -p 8080:80 -d nginx