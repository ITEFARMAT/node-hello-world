## Run locally

```bash
npm install
npm start
```

## Run in a container

```bash
docker build -t node-hello-world:latest .
docker run -it -p 8080:8080 --name node-hello-world node-hello-world:latest
```
