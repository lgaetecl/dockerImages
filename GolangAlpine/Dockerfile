FROM golang:alpine
LABEL maintainer="lgaete.astudillo@gmail.com"

RUN apk add --no-cache --virtual make
RUN apk add --no-cache --virtual git 
RUN apk add --no-cache --virtual bash
RUN apk add --no-cache --virtual openssl
RUN go get -u github.com/go-swagger/go-swagger/cmd/swagger 