# FROM almalinux:9 
# ENV course="devops with AWS" \
#     trainer="ramu gorla" \
#     duration="120HRS"
# RUN echo "Hello ${course}" > /tmp/devops.txt
# CMD ["sleep", "100"]

# ENV instruction variables can be accessed during build time and also inside the container our applications


FROM almalinux:9 
ENV course="devops with AWS" \
    trainer="ramu gorla" \
    duration="120HRS"
ARG USERNAME=RAMUGORLA
ENV USERNAME=$USERNAME
# 16th line is to make the ARG variables accessible inside the container
RUN echo "Hello ${USERNAME}" > /tmp/devops.txt
CMD ["sleep", "100"]