FROM alpine:latest
RUN apk add squid
RUN apk add apache2-utils
RUN htpasswd -bc /etc/squid/passwd foo bar
COPY squid.conf /etc/squid/squid.conf
CMD /usr/sbin/squid --foreground
