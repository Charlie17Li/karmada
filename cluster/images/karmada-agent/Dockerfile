FROM alpine:3.7

RUN echo -e http://mirrors.ustc.edu.cn/alpine/v3.7/main/ > /etc/apk/repositories

RUN apk add --no-cache ca-certificates

ADD karmada-agent /bin/

CMD ["/bin/karmada-agent"]
