FROM circleci/node:latest

LABEL maintainer="Ru Chern Chong"

RUN sudo apt-get update && sudo apt-get install -y yarn awscli

RUN command -v aws
RUN yarn -v
RUN node -v