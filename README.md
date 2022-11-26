## Run locally

```bash
yarn
yarn start
```

## Run in a container

```bash
docker build -t node-hello-world:latest .
docker run -it -p 80:80 --name ${app_name} ${image}
```
