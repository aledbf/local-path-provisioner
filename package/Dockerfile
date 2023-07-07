FROM alpine

RUN  apk upgrade --no-cache \
  && apk add --no-cache busybox zlib

COPY bin/local-path-provisioner /usr/bin/
CMD ["local-path-provisioner"]
