FROM rabbitmq:3.11.8-management

RUN ln -snf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
RUN apt-get update && apt-get install -y vim

EXPOSE 15672
EXPOSE 5672
