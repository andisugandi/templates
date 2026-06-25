ARG PROMETHEUS_VERSION=v3.12.0

FROM prom/prometheus:$PROMETHEUS_VERSION

LABEL org.opencontainers.image.authors="andisugandi@gmail.com"

COPY config/prometheus.yml /etc/prometheus/prometheus.yml
