Elasticsearch 1.7.5 Docker Image
===

#### build image from Dockerfile
```bash
docker build -t elasticsearch:1.7.5 .
```


#### create docker container form this image
```bash
docker run -it -p 9200:9200 -p 9300:9300 elasticsearch:1.7.5
```