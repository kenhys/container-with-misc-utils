FROM --platform=linux/arm64 arm64v8/debian:bookworm-slim

RUN apt-get update \
 && apt-get install -y --no-install-recommends \
    ca-certificates \
    curl wget iproute2 netcat-openbsd iputils-ping

CMD ["bash"]
