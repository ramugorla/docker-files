FROM almalinux:9 
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]

#COPY instruction is used to copy the files from the local workspace into the image or container.