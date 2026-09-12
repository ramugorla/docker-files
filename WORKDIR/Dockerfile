FROM almalinux:9 
RUN dnf install nginx -y 
RUN mkdir /tmp/work-dir-demo/
#RUN cd /tmp/work-dir-demo/
WORKDIR /tmp/work-dir-demo/
RUN pwd 
RUN echo "Hello world" > hello.txt
#RUN ls  will run during image build time only 
CMD ["nginx", "-g", "daemon off;"]


# In containers cd (change directory) will not work so we has to set the work directory path with WORKDIR instrction 