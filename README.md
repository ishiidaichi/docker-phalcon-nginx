# docker-phalcon-nginx
Phalcon PHP with nginx on docker ubuntu

just run :

```
#pull an image
docker pull ishiidaichi/docker-phalcon-nginx

# run your Phalcon PHP app!
docker run -d -p 80:80 -v /path/to/your/app:/var/www/html ishiidaichi/docker-phalcon-nginx
```

That's it!
