ARG version
FROM almalinux:${version:-9}
ENV course="devops with aws" \
    trainer="Niharika" \
    duration="120hrs"
ARG USERNAME=Niharika
ENV USERNAME=$USERNAME
RUN echo "Hello user: ${USERNAME}, image version: ${version}"> /tmp/devops.txt
CMD ["sleep", "100"]