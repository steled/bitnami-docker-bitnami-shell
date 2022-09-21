FROM docker.io/bitnami/minideb:buster
LABEL maintainer "Bitnami <containers@bitnami.com>"

COPY 10/debian-10/prebuildfs /
# Install required system packages and dependencies
RUN install_packages curl procps

# Bitnami Version: 10-debian-10-r160
ENV BITNAMI_APP_NAME="bitnami-shell" \
    BITNAMI_IMAGE_VERSION="10-debian-10-r160" \
    OS_ARCH="arm64" \
    OS_FLAVOUR="debian-10" \
    OS_NAME="linux"

