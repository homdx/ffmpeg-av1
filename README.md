# ffmpeg-av1

## Docker builder for latest ffmpeg version with AV1 codecs support

![docker status](https://github.com/homdx/ffmpeg-av1/actions/workflows/docker-image.yml/badge.svg)

# Docker images:

`docker run homdx/ffmpeg-av1 -version`

2023.05 Runtime `docker run homdx/ffmpeg-av1:debian-23.05 -version` and `docker run homdx/ffmpeg-av1:ubuntu-23.05`
        With sources: `homdx/ffmpeg-av1:src-debian-23.05` and `homdx/ffmpeg-av1:src-ubuntu-23.05`

```
#With sources
docker run homdx/ffmpeg-av1:debian-23.05 /home/homdx/bin/ffmpeg -version
ffmpeg version N-110562-g9f4df9a535 Copyright (c) 2000-2023 the FFmpeg developers
built with gcc 10 (Debian 10.2.1-6)
```

```
#With sources
docker run homdx/ffmpeg-av1:ubuntu-23.05 /home/homdx/bin/ffmpeg -version
ffmpeg version N-110562-g9f4df9a535 Copyright (c) 2000-2023 the FFmpeg developers
built with gcc 11 (Ubuntu 11.3.0-1ubuntu1~22.04)
```
