FROM golang:latest
RUN apt-get update -qq
RUN apt-get install -y mariadb-client
RUN echo "export PATH=$PATH:$GOBIN" > /root/.bashrc
