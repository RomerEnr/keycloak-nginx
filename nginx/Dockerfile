FROM nginx:1.25.2-alpine3.18
EXPOSE 80 443
COPY certs/* /etc/nginx/ssl/localhost/
COPY config/localhost.conf /etc/nginx/nginx.conf