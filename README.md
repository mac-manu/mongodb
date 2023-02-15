OCI runtime exec failed: exec failed: unable to start container process: exec: "mongo": executable file not found in $PATH: unknown


# to run 

docker run -d -p 27017:27017 --name=mongo-example mongo:latest

## to run mongo cli 
docker exec -it mongo-example mongosh
