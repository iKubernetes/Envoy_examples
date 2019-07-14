FROM envoyproxy/envoy-alpine:v1.10.0

ADD envoy.yaml /etc/envoy/

RUN apk update && apk --no-cache add curl
