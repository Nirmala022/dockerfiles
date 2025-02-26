ARG Version
FROM almalinux:${Version:-9}
ENV course="DevOps with aws" \
    trainer="sivakumar" \
    duration="120HRS"
# user1 is key,someuser is default value    
ARG USERNAME=Sivakumar   
RUN echo "hello user: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep","100"]     