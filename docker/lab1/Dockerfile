FROM ubuntu:18.04
LABEL francis abodo (abodojustin@gmail.com)
RUN apt-get update
RUN apt-get install -y nginx
ADD static-website-example/ /var/www/html/
EXPOSE 80
CMD [“nginx”, “-g”, “daemon off;”]