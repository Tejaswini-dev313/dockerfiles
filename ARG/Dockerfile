ARG version
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="120 Hrs"
ENV duration=${duration}
RUN echo "Course: $course, duration: $duration"
CMD ["sleep", "100"]