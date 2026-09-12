FROM almalinux:9 
RUN dnf install nginx -y 
CMD ["nginx", "-g", "daemon off;"]
# CMD instruction will execute at the time of container creation , CMD can be overridden during run time, The command whcih we are giving in CMD instruction should run the service or nginx infinite time