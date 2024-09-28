### README

This conatians the source code a Dockerfile for Newsbot project and also the dockerised file  and then use the Dockerfile to build a Docker image and run the container

### Building the Docker image

Build the image using the below command

```
docker build -t <docker image name>
```

Run the container using

```
docker run -e NBT_ACCESS_TOKEN=<token> <container name>
```

Replace `<token>` with the Telegram API Token that was generated.
