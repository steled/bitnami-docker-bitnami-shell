FROM docker.io/bitnami/minideb:buster
LABEL maintainer "Bitnami <containers@bitnami.com>"

COPY 10/debian-10/prebuildfs /
# Install required system packages and dependencies
RUN install_packages curl procps
RUN apt-get update && apt-get upgrade -y && \
    rm -r /var/lib/apt/lists /var/cache/apt/archives

# Bitnami Version: 10-debian-10-r424
ENV APP_VERSION="10" \
    BITNAMI_APP_NAME="bitnami-shell" \
    BITNAMI_IMAGE_VERSION="10-debian-10-r424" \
    OS_ARCH="arm64" \
    OS_FLAVOUR="debian-10" \
    OS_NAME="linux"
