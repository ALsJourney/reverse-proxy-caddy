# reverse-proxy-caddy


For local dev, add following lines to /etc/hosts
```
127.0.0.1 nodeapp.local
127.0.0.1 phpmyadmin.local
```

There is also an nginx implementation. Just use the nginx yml file and rename it

```bash
mv docker-compose.yml docker-compose.yml.caddy
mv docker-compose.yml.nginx docker-compose.yml
```

Or use the following command to switch between caddy and nginx

```bash
mv docker-compose.yml docker-compose.yml.caddy && mv docker-compose.yml.nginx docker-compose.yml
```
