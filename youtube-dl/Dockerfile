FROM alpine:3
RUN apk add python3 py3-pip ca-certificates ffmpeg gcc libc-dev
RUN rm -rf /var/cache/apk/*
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED && python3 -m ensurepip && pip3 install -U yt-dlp
CMD ["/bin/sh"]
