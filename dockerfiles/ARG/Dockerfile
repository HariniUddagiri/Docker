ARG version
FROM almalinux:${version:-9}
ENV Project="expense" \
    Component="frontend" \
    environment="dev"
ARG username=Harini
RUN echo "Hello user:${username}" >/tmp/devops.txt
#just saved in file, but arg vriables can't be accessed inside container
CMD ["sleep", "100"]