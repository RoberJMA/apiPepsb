FROM httpd
USER root
RUN apt update; \
    apt upgrade;
COPY ./httpd.conf /usr/local/apache2/conf/

# RUN sed -i '/#LoadModule proxy_module/s/^#//g' /usr/local/apache2/conf/httpd.conf
# RUN sed -i '/#LoadModule proxy_http_module/s/^#//g' /usr/local/apache2/conf/httpd.conf