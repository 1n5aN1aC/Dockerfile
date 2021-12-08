FROM alpine:3
RUN apk add python3 py3-pip ca-certificates ffmpeg gcc libc-dev
RUN rm -rf /var/cache/apk/*
RUN pip3 install -U yt-dlp
CMD ["/bin/sh"]