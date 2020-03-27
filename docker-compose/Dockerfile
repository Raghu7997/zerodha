FROM golang:1.13
WORKDIR /go/src/app

COPY ops-interview-task-master /go/src/app/ops-interview-task-master

WORKDIR /go/src/app/ops-interview-task-master

RUN make 

EXPOSE 8000

