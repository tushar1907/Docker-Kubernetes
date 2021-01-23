FROM httpd

WORKDIR /usr/local/apache2/htdocs/

COPY ./index.html .
# ADD ./index.html . this will do the same job as COPY but ADD will copy the resources from URLS

EXPOSE 80

CMD apachectl -D FOREGROUND