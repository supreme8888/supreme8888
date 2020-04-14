FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python postgreaql-client py-pip && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
