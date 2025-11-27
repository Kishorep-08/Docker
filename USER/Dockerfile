FROM almalinux:9
LABEL Maintainer="kishore8856"
RUN dnf install nginx -y \
    && useradd kishore

USER kishore

CMD ["sleep", "1000"]