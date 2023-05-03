FROM envoyproxy/envoy:dev-fa5764722370191760aa77309345192cdbfb6ea4

RUN mkdir -p /etc/envoy
#COPY ./envoy.yaml /etc/envoy/envoy.yaml

CMD ["/usr/local/bin/envoy","-c","/etc/envoy/envoy.yaml","--service-cluster","envoy","--service-node","envoy","--log-level","debug"]
