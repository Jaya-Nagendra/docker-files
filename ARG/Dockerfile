ARG version
#version is an variable default was 8
FROM almalinux:${version:-8}
# these variables are acceseble for only in image building time
ARG COURSE="Docker" \
    TRAINER="Sivakumar" \
    DURATION="10HRS" \
    AUTHOR="joindevops"
RUN echo "Trainer is: ${TRAINER}, version is: ${version}"
# version was not acceseble after FROM 
CMD ["sleep", "200"]
