FROM almalinux:9
ENV course="DevOps with aws" \
    trainer="sivakumar" \
    duration="120HRS"
# user1 is key,someuser is default value    
ARG ${username:-some_user}     
RUN echo "hello user: ${username}" 
CMD ["sleep","100"]     