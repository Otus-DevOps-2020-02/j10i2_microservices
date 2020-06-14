FROM golang:1.13

LABEL maintainer="Meik Minks <mminks@inoxio.de>"

RUN go get -u github.com/percona/mongodb_exporter

WORKDIR /go/src/github.com/percona/mongodb_exporter

RUN make build

FROM quay.io/prometheus/busybox:latest

LABEL maintainer="Alexey Palazhchenko <alexey.palazhchenko@percona.com>"

COPY --from=0 /go/src/github.com/percona/mongodb_exporter/bin/mongodb_exporter /bin/mongodb_exporter

EXPOSE 9216

ENTRYPOINT [ "/bin/mongodb_exporter" ]
