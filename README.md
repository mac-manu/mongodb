
docker pull mongo || docker pull mongo:latest

# to run 

docker run -d -p 27017:27017 --name=mongo-example mongo:latest

## to run mongo cli 
docker exec -it mongo-example mongosh


