# Docker

> Docker images for `thumbsup`

Images are built automatically on DockerHub, and published to
https://hub.docker.com/r/thumbsupgallery.

| Image | Contents | Purpose |
|-------|----------|---------|
| `runtime:alpine` | Node.js + graphicsmagick + ffmpeg + exiftool | Base image |
| `build:alpine` | Runtime + build tools (git, make...) + pre-built SQLite | Speed up the builds |
| `thumbsup` | Runtime + thumbsup | Final usable image |

See the individual folders for details of the images,
and the website for the full documentation: https://thumbsup.github.io.
