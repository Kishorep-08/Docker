ARG VERSION
FROM almalinux:${VERSION:-9}
ARG name="Kishore" \
    course="Docker"
RUN echo "Hello ${name}, Welcome to the ${course} Course!"
ENV name=${name} \
    course=$course
CMD ["sleep", "500"]
