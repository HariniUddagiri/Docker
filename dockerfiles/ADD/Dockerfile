FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/HariniUddagiri/Docker/refs/heads/main/dockerfiles/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"] 