FROM envoyproxy/envoy:dev-fa5764722370191760aa77309345192cdbfb6ea4

RUN mkdir -p /etc/envoy
RUN apt-get update && apt-get install -y vim
#COPY ./envoy.yaml /etc/envoy/envoy.yaml

CMD ["/usr/local/bin/envoy","-c","/etc/envoy/envoy.yaml","--service-cluster","envoy","--service-node","envoy","--log-level","info"]
