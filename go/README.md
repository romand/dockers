
## Using


## Building an image for your Go app

TODO: Build it into a base image, don't really need Go in it.

## Building this image

```sh
docker build -t iron/go:latest .
```

Tag it with Go version too: (can check with `docker run --rm iron/go version`):

```sh
docker tag iron/go:latest iron/go:1.4.2
```

Push:

```sh
docker push iron/go
```
