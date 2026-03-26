FROM mongo:5
COPY *.js /docker-entrypoint-initdb.d/

## Now once we run this dockerfile. it will pull the mongodb OS and copies the user.js and catalogue.js file to the server and loads the data.


##Command to build the image:
## docker build -t <image_name>:<version> .
## While building the image we should stand at dockerfile 

## Commad to run the contianer:
## docker run -d --name <container_name> <image_name>:<version>
## -p port forwarding is not required as we are not accessing the container from outside

## Command to check logs:
## docker logs <container_name>

## When ever we do changes in a image we have to build it again.