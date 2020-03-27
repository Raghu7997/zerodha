FROM golang:1.13
WORKDIR /go/src/app

COPY ops-interview-task-master /go/src/app/ops-interview-task-master

WORKDIR /go/src/app/ops-interview-task-master

RUN make 
ENV DEMO_APP_ADDR=18.206.185.206:8000
ENV DEMO_REDIS_ADDR=18.206.185.206:6379

EXPOSE 8000

CMD go run main.go
