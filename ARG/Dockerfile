ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with aws" \
    trainer="sivakumar" \
    duration="120HRS"
# user1 is key,someuser is default value    
ARG USERNAME=Sivakumar   
RUN echo "hello user: ${USERNAME},image version: ${version}" > /tmp/devops.txt
CMD ["sleep","100"]     