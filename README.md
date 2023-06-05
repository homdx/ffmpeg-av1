# ffmpeg-av1

## Docker builder for latest ffmpeg version with AV1 codecs support

![docker status](https://github.com/homdx/ffmpeg-av1/actions/workflows/docker-image.yml/badge.svg)

# Docker images:

`docker run homdx/ffmpeg-av1 -version`

2023.06 Runtime `docker run homdx/ffmpeg-av1:debian-23.06 -version` and `docker run homdx/ffmpeg-av1:ubuntu-23.06`

With sources: `homdx/ffmpeg-av1:src-debian-23.06` and `homdx/ffmpeg-av1:src-ubuntu-23.06`

Changes from 2023.05: Added `libvidstab,libfreetype,libmp3lame`

```
#With sources
docker run homdx/ffmpeg-av1:debian-23.06 /home/homdx/bin/ffmpeg -version
ffmpeg version N-111016-gfa11c4c7fa Copyright (c) 2000-2023 the FFmpeg developers
built with gcc 10 (Debian 10.2.1-6)
```

```
#With sources
docker run homdx/ffmpeg-av1:ubuntu-23.06 /home/homdx/bin/ffmpeg -version
ffmpeg version N-111016-gfa11c4c7fa Copyright (c) 2000-2023 the FFmpeg developers
built with gcc 11 (Ubuntu 11.3.0-1ubuntu1~22.04.1)
```
