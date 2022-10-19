# 03 - Docker - 
## Orchestrer avec docker compose

 ✨Magic ✨

## Docker

By default, the Docker will expose port 8080, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```sh
cd quest_3
docker compose -f docker-compose.dev.yml up --build
```

This will create the quest_3 images and pull in the necessary dependencies.
# quest_3
