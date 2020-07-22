FROM alpine:3.11
RUN apk update \
	&& apk add py-pip ca-certificates \
	&& apk add ffmpeg \
	&& rm -rf /var/cache/apk/*
RUN pip install youtube-dl
CMD ["/bin/sh"]
