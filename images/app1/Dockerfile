# base image from my image is created
FROM httpd

# copy the index.html to htdocs directory
COPY ./index.html /usr/local/apache2/htdocs

# expose port 80 to the listen for incoming request
EXPOSE 80

# run apache in foreground
CMD apachectl -D FOREGROUND



