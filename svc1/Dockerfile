FROM golang:1.8.0
EXPOSE 61001
CMD ["svc1"]
COPY . /go/src/github.com/jhayotte/linkerdsidecar/svc1
WORKDIR /go/src/github.com/jhayotte/linkerdsidecar/svc1
RUN make install