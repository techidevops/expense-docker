FROM almalinux:9
RUN sudo apt-get install nginx -y
RUN sudo rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off" ]