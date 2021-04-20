FROM ubuntu:16.04
RUN apt update && apt install nginx -y
COPY index.html /var/www/html
ENTRYPOINT ["nginx", "-g", "daemon off;"]
