ARG SQS_VERSION
FROM roribio16/alpine-sqs:${SQS_VERSION}

LABEL maintainer="Ronald E. Oribio R. https://github.com/roribio"

ENTRYPOINT ["bash", "-c", "/usr/bin/supervisord"]

EXPOSE 9324 9325
