# docker-nginx-reverse-proxy

# 1. Create docker network 
```
docker network create {your-network-name}
```

# 2.Build docker with docker-composer
```
docker-compose  up -d
```


### Example nginx config file
 - HTTP
    - nginx/conf.d/file.server.com.conf
    - nginx/conf.d/mail.server.com.conf

 - HTTPS/SSL
    - nginx/conf.d/domain.com.conf 