ARG version
FROM almalinux:${version:-9}
ARG course="Devops with AWS" \
    trainer="siva kumar reddy" \
    duration="120 hrs"
ENV duration=$duration
RUN echo "Course : $course, duration is $duration"
CMD ["sleep", "100"]