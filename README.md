# docker-images
Some useful docker images

Images are uploaded to docker hub: https://hub.docker.com/u/intesys

### Build image manually
```bash
$ docker login
$ docker build -t intesys/<image-name>:<image-tag> .
$ docker push intesys/<image-name>:<image-tag>
```