FROM almalinux:9
RUN dnf install nginx -y 
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]

# [command, arg1, arg2] --- command, options/parameter ,  argumnet value --- executable format
# Docker supports Shell and executable format 
# shell -- CMD command arg1  arg2  = CMD nginx -g "daemon off;"