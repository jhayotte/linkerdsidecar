FROM golang:1.8.0
EXPOSE 61002
CMD ["svc2"]
COPY . /go/src/github.com/jhayotte/linkerdsidecar/svc2
WORKDIR /go/src/github.com/jhayotte/linkerdsidecar/svc2
RUN make install