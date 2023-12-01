# nginx-playground

Playground for [Learning NGINX](https://www.linkedin.com/learning/learning-nginx-17014605)

## Setup

[Run an NGINX proxy on Fly](https://fly.io/docs/app-guides/global-nginx-proxy/)

* create `Dockerfile`
* create `nginx.conf`
* `fly launch`
* `fly deploy`
* `fly open`

## Verify

* `fly ssh console`
* `nginx -v`
* `service nginx status`
* https://nginx-playground.fly.dev
* verify configuration `nginx -t`
* display configuration `nginx -T`

## Service

```
/etc/init.d/nginx {start|stop|status|restart|reload|force-reload|upgrade|configtest|check-reload}
```

### Reload

Will reload configuration without stoping service.

## Directories

### Configuration

`/etc/nginx/`

### Logs

`/var/log/nginx`

