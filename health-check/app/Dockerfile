FROM golang:1.19.3-alpine

RUN apk --no-cache add curl
RUN mkdir app
COPY main.go app

EXPOSE 8089

CMD go run app/main.go