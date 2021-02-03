FROM alpine:latest
RUN apk add squid
COPY squid.conf /etc/squid/squid.conf
CMD /usr/sbin/squid --foreground
