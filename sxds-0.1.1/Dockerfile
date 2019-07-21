FROM alpine:3.10.1

LABEL version="0.1.1"

ADD sxds /usr/bin/

ENV SXDS_PRODUCTION=false SXDS_ADS_MODE=false SXDS_XDS_PORT=8081 SXDS_CACHER_PORT=8082

# RUN  apk add --no-cache curl

EXPOSE 8081 8082

CMD ["/usr/bin/sxds"]  
