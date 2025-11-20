ARG CODE
FROM almalinux:${CODE:-9}
ARG COURSE="DevOps" \
    Trainer="Siva" 
RUN echo "TRAINER is : ${Trainer}, COURSE is : ${COURSE}, CODE is : ${CODE}"
ENV COURSE=${COURSE}
CMD [ "sleep", "1000" ]
