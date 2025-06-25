# Qdrant Setup

All you need to do is pull the image and start the container using the following commands:

```bash
docker pull qdrant/qdrant

docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant
```

* Install libraries
    - `qdrant-client` 
    - `fastembed`


