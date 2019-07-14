FROM envoyproxy/envoy-alpine:v1.11.0

ADD envoy.yaml eds.conf eds.conf.v2 envoy-cds.yaml cds.conf /etc/envoy/

RUN apk update && apk --no-cache add curl
