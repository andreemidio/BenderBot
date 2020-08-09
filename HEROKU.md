# DEPLOY
the name app on heroku is "opencv-bender"

## FIRST DEPLOY
```
$ heroku login
$ docker ps
$ heroku container:login
$ heroku container:push web --app opencv-bender
$ heroku container:release web --app opencv-bender
```

## NEXT UPDATES

```
$ heroku container:release web --app opencv-bender
```