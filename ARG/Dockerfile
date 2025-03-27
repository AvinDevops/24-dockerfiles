ARG version
FROM almalinux:${version:-8}
ARG COURSE=Docker
ARG TRAINER=Avin
ARG Duration=120hrs
ENV Duration=${Duration}
ENV TRAINER=${TRAINER}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER} and Duration is: ${Duration}"
CMD ["sleep", "200"]