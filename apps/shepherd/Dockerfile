FROM docker
MAINTAINER support@dapla.net

ENV SLEEP_TIME='5m'

COPY shepherd /usr/local/bin/shepherd

ENTRYPOINT ["/usr/local/bin/shepherd"]
HEALTHCHECK CMD ["exit", "0"]
RUN apk add --update --no-cache bash
