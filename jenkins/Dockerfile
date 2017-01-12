FROM jenkins

USER root 

RUN apt-get update && \
    apt-get install -y --no-install-suggests --no-install-recommends sudo && \
    rm -rf /var/lib/apt/lists/*

COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]