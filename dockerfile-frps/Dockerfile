FROM alpine:latest
COPY frps /usr/local/bin/
COPY frps.ini /etc/
CMD ["frps", "-c", "/etc/frps.ini"]