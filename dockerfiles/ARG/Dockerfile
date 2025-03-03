ARG version
FROM almalinux:${version:-9}
ENV Project="expense" \
    Component="frontend" \
    environment="dev"
ARG username=Harini
ENV username=$username 
#setting arg variable to env , so that arg variable can be accessed inside container
RUN echo "Hello user:${username},image version:{version}" >/tmp/devops.txt
#just saved in file, but arg vriables can't be accessed inside container
CMD ["sleep", "100"]