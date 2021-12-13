FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3
RUN install awscli
RUN apk --purge -v del python3
CMD tail -f /dev/null
