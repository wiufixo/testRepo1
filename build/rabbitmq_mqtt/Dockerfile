FROM rabbitmq:3.11.8-management

RUN ln -snf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
RUN rm /etc/rabbitmq/conf.d/10-defaults.conf
RUN rabbitmq-plugins enable --offline rabbitmq_mqtt

RUN apt-get update && apt-get install -y vim

EXPOSE 15672
EXPOSE 1883
