FROM almalinux:9 
RUN dnf install nginx -y 
RUN mkdir /tmp/work-dir-demo/
RUN cd /tmp/work-dir-demo/
RUN pwd 
RUN echo "Hello world" > hello.txt
RUN ls
CMD ["nginx", "-g", "daemon off;"]
