FROM alpine
#By default, it will pull down the latest version (same as FROM alpine:latest)

RUN apk add --no-cache python3 py3-pip
#Will install python (originally "RUN apt add python" but had to tweak it to get it to work)

CMD ["8.8.8.8"]

ENTRYPOINT [ "ping", "-t", "5" ]
# Syntax: ENTRYPOINT ["executable"]  .... In this case, will run ping five times on the ip above