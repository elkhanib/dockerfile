FROM nginx:1.13.3

RUN apt-get update && apt-get install -y curl

HEALTHCHECK --interval=15s CMD /usr/bin/curl -Sf http://localhost || exit 1
