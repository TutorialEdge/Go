FROM golang:1.10.1
ENV GOPATH=/go
WORKDIR /go/app
ADD . /go/app
RUN go get -d -v github.com/googollee/go-socket.io
RUN go build -o main .
RUN ls
RUN pwd
CMD ["/go/app/main"]