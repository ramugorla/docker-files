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
RUN echo "Hello ${USERNAME}" > /tmp/devops.txt
CMD ["sleep", "100"]