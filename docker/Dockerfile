FROM cr.loongnix.cn/library/openjdk:8-buster

MAINTAINER Zewei Yang <yangzewei@loongson.cn>

WORKDIR /var/app

COPY zkui-*.jar /var/app/zkui.jar
COPY config.cfg /var/app/config.cfg
COPY bootstrap.sh /var/app/bootstrap.sh

ENTRYPOINT ["/var/app/bootstrap.sh"]

EXPOSE 9090
