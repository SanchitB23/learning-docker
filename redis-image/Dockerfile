#Use existing Docker image as base

FROM alpine

# Download and install dependancy

RUN apk add --update redis

# Tell image what to do when it starts

CMD [ "redis-server" ]  