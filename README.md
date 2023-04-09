# imagesearch
We use weaviate to create a simple image search engine. 

I used the fireship tutorial on how to create weviate. His code incorrect. I used chatgpt to troubleshoot. 
- must install node
- must install docker 

command line to use.

```
curl -o docker-compose.yml "https://configuration.weaviate.io/v2/docker-compose/docker-compose.yml?generative_openai=false&image_neural_model=pytorch-resnet50&media_type=image&modules=modules&ref2vec_centroid=false&runtime=docker-compose&weaviate_version=v1.18.3"
```

```
docker-compose up -d
```

```
node app.js
```

Watched tutorial from fireship to get it work. https://youtu.be/mBcBoGhFndY

