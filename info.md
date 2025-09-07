# Complete (chapter 2-7)

### OAuth authentication to run on secure certificate/ certificate not valid / just to run in development

set 127.0.0.1 mysite.com in your local hosts file in sys32

```
python manage.py runserver_plus --cert-file cert.crt
```

## To run the redis image on docker

```
docker run -it --rm --name redis -p 6379:6379 redis
```

## Todo

- improve css, make it presentable
- deploy
