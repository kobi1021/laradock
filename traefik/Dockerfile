ARG TRAEFIK_VERSION
FROM traefik:${TRAEFIK_VERSION}

LABEL maintainer="Luis Coutinho <luis@luiscoutinho.pt>"

WORKDIR /data

RUN touch acme.json

RUN chmod 600 acme.json

VOLUME /data