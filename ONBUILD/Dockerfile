FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/shar/nginx/html/index.html
ONBUILD COPY index.html /usr/shar/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]