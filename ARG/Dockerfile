ARG version
FROM almalinux:{version:-9}
ENV course="devops" \
    trainer="bhanu" \
    duration="120HRS"
ARG USERNAME=BhanuPrakash
ENV USERNAME=$USERNAME
RUN echo "Hello user :${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep" , "100"]