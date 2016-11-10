FROM kibana:5.0

EXPOSE 5601:5601

RUN gosu kibana kibana plugin --install elasticsearch/marvel
RUN gosu kibana kibana plugin --install elastic/sense

MAINTAINER Alexandr Kulitsky <kulitsky@targetprocess.com>
