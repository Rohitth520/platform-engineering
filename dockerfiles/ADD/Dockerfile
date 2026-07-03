FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Rohitth520/platform-engineering/refs/heads/main/dockerfiles/RUN/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]