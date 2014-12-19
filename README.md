mbentley/mongodb2.4
==================

docker image for mongodb
based off of stackbrew/ubuntu:12.04

To pull this image:
`docker pull mbentley/mongodb2.4`

Example usage:
`docker run -itd -p 27017:27017 -p 28017:28017 -e MONGODB_USER=admin -e MONGODB_PASS=mongo -e MONGODB_DB=mongo mbentley/mongodb2.4`

The following environment variables can be passed to the docker image:

`MONGODB_USER` (default: admin)

`MONGODB_PASS` (default: mongo)

`MONGODB_DB` (default: mongo)
