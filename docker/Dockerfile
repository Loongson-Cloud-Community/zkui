FROM cr.loongnix.cn/library/openjdk:8-buster

MAINTAINER Zewei Yang <yangzewei@loongson.cn>

WORKDIR /var/app

ADD zkui-*.jar /var/app/zkui.jar
ADD config.cfg /var/app/config.cfg
ADD bootstrap.sh /var/app/bootstrap.sh

ENTRYPOINT ["/var/app/bootstrap.sh"]

EXPOSE 9090
