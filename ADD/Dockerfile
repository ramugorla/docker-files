FROM almalinux:9 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/ramugorla/docker-files/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]

# ADD Instruction is similer to COPY Instruction like copies the files into images, but ADD has 2 extra features like ADD will directly downloads the files from internet and also untar the tar files directly into container.
