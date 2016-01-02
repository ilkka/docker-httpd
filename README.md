# ilkka/httpd

Light customization on top of official Apache httpd image. Allows
dynamically specifying `ServerName` by setting `SERVER_NAME` in the
environment when running containers.

```
$ docker run -d --name my-httpd -e SERVER_NAME=foobar.example.com ilkka/httpd
```
