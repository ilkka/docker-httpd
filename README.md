# Supported tags

- [`2.4`, `2`, `latest` (*Dockerfile*)](https://github.com/ilkka/docker-httpd/blob/master/Dockerfile)

# What is this image?

Light customization on top of official Apache httpd image. Allows
dynamically specifying `ServerName` by setting `SERVER_NAME` in the
environment when running containers.

# How to use this image

```
$ docker run -d --name my-httpd -e SERVER_NAME=foobar.example.com ilkka/httpd
```
