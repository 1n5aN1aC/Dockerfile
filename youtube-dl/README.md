## youtube-dl

Environment for running [youtube-dl](https://github.com/rg3/youtube-dl) in docker.

* built on top of `alpine` base image
* includes `ffmpeg` in order to allow `youtube-dl` stitch together high quality videos, which are generally served as separate audio and video tracks
* `youtube-dl` is NO LONGER the entrypoint of the image
* 124 MB

### Example usage:

Download a video:
load a cronjob into /etc/periodic/daily/
