FROM golang:1.12.0

WORKDIR /go/src/app
COPY main.go go.mod ./

ENV GO111MODULE=on
RUN go build .

EXPOSE 3000
CMD [ "./main" ]
