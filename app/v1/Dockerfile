FROM golang:1.9

ADD . /go/src/github.com/rerorero/shadowing-test/app
RUN go install github.com/rerorero/shadowing-test/app
ENTRYPOINT /go/bin/app
EXPOSE 80
