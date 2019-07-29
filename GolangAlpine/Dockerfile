FROM golang:alpine
LABEL maintainer="lgaete.astudillo@gmail.com"

RUN apk add --no-cache build-base
RUN apk add --no-cache make
RUN apk add --no-cache git 
RUN apk add --no-cache bash
RUN apk add --no-cache openssl
RUN apk add --no-cache protobuf
RUN go get -u github.com/golang/protobuf/protoc-gen-go
RUN apk add --no-cache upx
