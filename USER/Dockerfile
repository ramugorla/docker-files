FROM almalinux:9
#RUN dnf install nginx -y 
# This RUN and CMD instructions in 2 and last line will not work with non root user
RUN useradd expense
USER expense
CMD ["sleep", "100"]
#CMD ["nginx", "-g", "daemon off;"]


# USER is used to create the non root user and get the container access as the non root user

