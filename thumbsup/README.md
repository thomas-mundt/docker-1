# thumbsupgallery/thumbsup

> Docker image for `thumbsup`

See the [Thumbsup website](https://thumbsup.github.io) for the full documentation.
See the [DockerHub page](https://hub.docker.com/r/thumbsupgallery/thumbsup/) for all available tags.

## Building this image

The image simply wraps a published version of thumbups + all runtime dependencies.
It is built automatically on DockerHub:

- Update the `VERSION` file and tag the commit as `x.y.z` to match the version
- DockerHub will build the image and publish it as `thumbsupgallery/thumbsup:x.y.z`
