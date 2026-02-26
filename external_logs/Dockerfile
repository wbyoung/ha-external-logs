ARG BUILD_FROM
FROM $BUILD_FROM

# Setup base
RUN \
    apt-get update \
    && apt-get install -y --no-install-recommends \
        systemd

# Copy data
COPY rootfs /
