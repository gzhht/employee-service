
- Run mogodb for local test
```
docker run -d --restart --name mongo-for-local  -p 27888:27017 -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=admin mongo
```