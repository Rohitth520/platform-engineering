ARG version
FROM almalinux:${version:-9}
ENV project="Platform Engineering" \
    author="Rohitth Pushkekar" \
    region="us-east-1"
#here user1 is key, someuser is default value
ARG USERNAME=Rohitth
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]