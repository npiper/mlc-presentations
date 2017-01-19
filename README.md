# MLC Reveal.js Presentation in a Box


## Base

The Docker reveal.js container at https://hub.docker.com/r/danidemi/docker-reveal.js/

## Deploy to Heroku

## Build

```
docker build -t "mlctech/docker-reveal.js:latest" .
```

### Run for the first time

```
docker -d -p 8000:8000 -v $(PWD):/slides run mlctech/docker-reveal.js
```

Go to your docker URL at port 8000 (to check this use `docker-machine env`

http://localhost:8000

### Create your slideshow


### Run

