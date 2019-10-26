# Get Ubuntu 19.04
FROM ubuntu:19.04

# Navigate to src, install dependencies
RUN apt-get update && apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_13.x | bash
RUN apt-get update && apt-get install nodejs -y
