# Dockerize-SvelteKit-App
Dockerized SvelteKit Demo app

#### How to run this app in docker - 

> Step 1 : `Build Docker Image my-app`

```
docker build -t my-app:1 .
```

> Step 2 : `Run Docker Container for Image my-app`

```
docker run -d -p 3333:3333 --name blue_sky my-app:1
```
> Step 3 : `Browse http://localhost:3333/`
