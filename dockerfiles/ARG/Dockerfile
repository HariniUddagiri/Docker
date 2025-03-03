ARG version
FROM almalinux:${version:-9}
ENV Project="expense" \
    Component="frontend" \
    environment="dev"
ARG username=Harini
ENV username=$username
RUN echo "Hello user:${username},image version:{version}" >/tmp/devops.txt
#just saved in file, but arg vriables can't be accessed inside container
CMD ["sleep", "100"]