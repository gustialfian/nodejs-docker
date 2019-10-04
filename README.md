# wew
```bash
docker build --tag=gustialfianmp/nodejs-docker .

docker build --tag=gustialfianmp/nodejs-docker --target prod .
docker build --tag=gustialfianmp/nodejs-docker --target test .
docker build --tag=gustialfianmp/nodejs-docker --target dev .
docker build --tag=gustialfianmp/nodejs-docker --target source .

docker run -p 7000:3000 gustialfianmp/nodejs-docker
```