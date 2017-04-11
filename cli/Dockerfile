FROM golang:1.8.0
EXPOSE 61001
CMD ["cli"]
COPY . /go/src/github.com/jhayotte/linkerdsidecar/cli
WORKDIR /go/src/github.com/jhayotte/linkerdsidecar/cli
RUN make install