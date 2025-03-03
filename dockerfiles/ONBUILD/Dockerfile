FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#onbuild executes when someone is using or image as base OS
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]