FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
RUN apt-get update && apt-get install -y vim

# container 실행 시 자동으로 실행할 command. nginx 시작함
CMD ["nginx", "-g", "daemon off;"]