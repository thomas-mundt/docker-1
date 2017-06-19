# thumbsupgalleries/thumbsup

> Docker image for `thumbsup`

Basic usage:

```bash
docker run -t              \
  -v `pwd`:/work           \
  -u $(id -u):$(id -g)     \
  thumbsupgalleries/thumbsup \
  thumbsup --input /work/media --output /work/gallery
```

See the [Thumbsup website](https://thumbsup.github.io) for the full documentation.
See the [DockerHub page](https://hub.docker.com/r/thumbsupgalleries/thumbsup/) for all available tags.
