# Dockerfile for Nginx 1.16 based on CentOS

Runs as user_id=900, group_id=900

## Usage 

```shell
$ docker run -d \
  -v /data/site.conf:/etc/nginx/conf.d/site.conf'
  -v /data/log:/var/log/nginx \
  -p 80:8080 \
  quay.io/idwrx/nginx
```

