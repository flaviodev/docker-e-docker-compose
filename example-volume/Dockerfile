# base image 
FROM node:latest

MAINTAINER Flavio de Souza

# using environment variable
ENV NODE_PORT=3000

# executing command of copy
COPY . /var/www

# setting working directory
WORKDIR /var/www

# runnig another command
RUN npm install

# command will be running on container start
ENTRYPOINT npm start

# exposing port 
EXPOSE $NODE_PORT


