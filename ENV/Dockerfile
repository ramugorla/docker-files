FROM almalinux:9 
RUN dnf install nginx -y 
ENV course="Devops with AWS" \
    trainer="siva kumar" \
    duration="120HRS"

RUN echo "Hello ${trainer}" > /tmp/devops.txt


# Variables which are defined in ENV instruction can be accessed during image build time and also inside the container
# variables which are defined in the ARG instrction can be accessed during image build time but not inside container, and it can be overridden by the command line during run time like --build-arg username=ramu