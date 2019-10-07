# wew
```bash
docker build --tag=gustialfianmp/nodejs-docker .

docker build --tag=gustialfianmp/nodejs-docker --target prod .
docker build --tag=gustialfianmp/nodejs-docker --target test .
docker build --tag=gustialfianmp/nodejs-docker --target dev .
docker build --tag=gustialfianmp/nodejs-docker --target source .

docker run -p 7000:3000 gustialfianmp/nodejs-docker

docker-compose up
```

## Resources
this repository is for learning purposes from this [video](https://www.youtube.com/watch?v=Zgx0o8QjJk4) and this [repo](https://github.com/bretfisher/dockercon19)