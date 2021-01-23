# use an exisiting docker base image 
FROM alpine

# Download and install dependencies
RUN apk add --update redis

# Tell the container what to do after it starts
CMD [ "redis-server" ]